

### Concise Definitions 

* **Constrained**: whether the action space is limited by predefined rules or operators (e.g., legal chess moves vs. unconstrained natural language).
* **Heterogeneous**: whether actions come from *different types* (e.g., “click button,” “type text,” “scroll page”), as opposed to being uniform.
* **State-Dependent**: whether the set of valid actions changes depending on the current environment state (e.g., you can only “pick up a mug” if one is present).

---

### Verification of Categorization

1. **Embodied Tasks**

   * Discrete ✓ (actions are predefined like “pick up,” “open door”)
   * Constrained: **Yes** (grammar of possible actions)
   * Heterogeneous: **Yes** (different types of interactions: pick, move, open)
   * State-Dependent: **Yes** (only available if object exists)
   * Action Reversible: **Maybe** (you can “drop” after “pick up,” but not always)
   * Execution: 🌐 Task-Essential

2. **Combinatorial Tasks (Game-of-24, Chess)**

   * Discrete ✓
   * Constrained: **Yes** (rules of math ops, chess moves)
   * Heterogeneous: **No** (all actions are uniform type: numbers/operators or chess moves)
   * State-Dependent: **Yes** (legal moves depend on current state)
   * Action Reversible: **Maybe** (some moves reversible, some not)
   * Execution: 🌐 Task-Essential

3. **Web Navigations (WebShop, WebArena)**

   * Discrete ✓
   * Constrained: **Yes** (set of clickable links, form options)
   * Heterogeneous: **Yes** (click, type, scroll, select)
   * State-Dependent: **Yes** 
       * because available links/forms *do* change with navigation.
       * ⚠️: Some would argue “state-dependent = No,” since the set of UI elements usually exists regardless
   * Action Reversible: **Maybe** (e.g., can click back, but not always reversible)
   * Execution: 🌐 Task-Essential
     

4. **Graph Traversal**

   * Discrete ✓
   * Constrained: **Yes** (edges define legal moves)
   * Heterogeneous: **No** (all moves are “go to neighbor node”)
   * State-Dependent: **No** (set of edges from a node is fixed, not dynamic)
   * Action Reversible: **Maybe** (depends if traversal allows backtracking)
   * Execution: 🌐 Task-Essential

5. **Reasoning (Concatenation)**

   * Open text ✓
   * Constrained: **No** (free text generation)
   * Heterogeneous: **No** (always text)
   * State-Dependent: **No** (actions are unconstrained thoughts)
   * Action Reversible: **Yes** (in principle, can revise reasoning)
   * Execution: 📝 Internal

6. **Reasoning via QAs**

   * Open text ✓
   * Constrained: **No**
   * Heterogeneous: **No**
   * State-Dependent: **No**
   * Action Reversible: **Yes**
   * Execution: 📝 Internal

7. **Reasoning with Tool Invocation**

   * Open text + tool calls ✓
   * Constrained: 
         * Text part: free-form, unconstrained (the LLM can output anything).
         * Tool calls: usually from a finite, predefined set of APIs (e.g., Calculator, Python.run, Search(query)), which is constrained.
   * Heterogeneous: **Yes** (mix of text and tool APIs)
   * State-Dependent: **No** (tools available independent of state, unless restricted)
   * Action Reversible: **Maybe** (depends on tool)
   * Execution: 🛠 Auxiliary External

8. **Reasoning over Knowledge Graph**

   * Discrete + triplets ✓
   * Constrained: **Yes** (relations and entities)
   * Heterogeneous: **Yes** (different relation types)
   * State-Dependent: **No** (triplets are fixed; graph doesn’t change during reasoning)
   * Action Reversible: **Yes** (can backtrack queries)
   * Execution: 🌐 Task-Essential

9. **Tool-based Tasks**

   * Discrete ✓
   * Constrained: **Yes** (set of allowed tools)
   * Heterogeneous: **Yes** (different APIs)
   * State-Dependent: **No**
   * Action Reversible: **Maybe** (depends on tool)
   * Execution: 🛠 Auxiliary External

10. **Code Generation**

    * Open text ✓
    * Constrained: **No** (unconstrained token generation)
    * Heterogeneous: **No** (all tokens are code)
    * State-Dependent: **No**
    * Action Reversible: **Yes** (can overwrite/edit code)
    * Execution: 📝 Internal

11. **Goal-oriented Dialog**

    * Discrete (intents) ✓
    * Constrained: **Yes** (limited intents)
    * Heterogeneous: **Yes** (different types of intents / utterances)
    * State-Dependent: **Yes** (valid intents depend on conversation history)
    * Action Reversible: **No** (dialogue acts cannot be undone)
    * Execution: 📝 Internal

---
