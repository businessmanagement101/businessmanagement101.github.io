---
icon: material/numeric-2
---


# **The Anatomy of a Great Concept Map** 🧠

A powerful concept map is built from a few simple components. Once you understand these building blocks, you can construct a sophisticated map on any topic. We'll use a simple, non-business example—"Making a Good Breakfast"—to illustrate each part.



### **1. Concepts**

**Concepts** are the key ideas or terms on your map. They are typically nouns and are enclosed in boxes or circles. Think of them as the main "landmarks" on your map.

* **Example:** `Breakfast`, `Coffee`, `Eggs`, `Heat`

---

### **2. Hierarchy**

**Hierarchy** is the arrangement of your concepts from the most general and inclusive at the top to the most specific at the bottom. The main idea you are exploring (usually from your focus question) should be at or near the top.

* **Example:** `Breakfast` is the most general concept, so it sits at the top. `Coffee` and `Eggs` are more specific components, so they branch out from below it.

---

### **3. Linking Words**

**Linking words** or phrases are the short verbs written on the lines that connect your concepts. **These are the most important part of the map.** They explain the *relationship* between two concepts and turn your map from a simple list into an argument. Without them, the map has no meaning.

* **Example:** `is made with`, `requires`, `can be`, `is influenced by`

---

### **4. Propositions**

A **proposition** is a complete thought or statement formed by two concepts joined by a linking phrase. It's the basic unit of meaning in your map. As you build your map, you should be able to read it like a series of sentences.

* **Example:** `[Coffee]` --- `requires` ---> `[Heat]`. This forms a clear, logical statement.

---

### **5. Cross-Links**

**Cross-links** are the most powerful part of a concept map. These are connections between concepts in *different branches* of your map. Finding cross-links is where deep learning and "aha!" moments happen, as they reveal the systemic nature of a topic.

* **Example:** A cross-link could show that the `[Heat]` used for the `Coffee` --- `is provided by the` ---> `[Stove]`, which is the same `[Stove]` used to cook the `[Eggs]`. This simple link shows the relationship between two different parts of the breakfast-making system.

## Example Concept Map


``` mermaid
graph TD
    subgraph Main Concept
        A[Breakfast]
    end

    subgraph Branch 1
        B(Coffee)
        E(Heat)
    end

    subgraph Branch 2
        C(Eggs)
        F(Stove)
    end
    
    subgraph Branch 3
        D(Pancakes)
        G(Syrup)
    end

    %% Defining the relationships (propositions)
    A -->|can include| B
    A -->|can include| C
    A -->|can include| D

    B -->|requires| E
    C -->|are cooked on a| F
    D -->|are cooked on a| F
    D -->|are topped with| G

    %% This is the cross-link between branches
    F -.->|provides the| E

    %% Styling nodes for clarity
    style A fill:#f9f,stroke:#333,stroke-width:2px
    linkStyle 7 stroke:#ff0000,stroke-width:2px,stroke-dasharray: 3 3;
```