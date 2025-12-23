# JavaScript Events – Core Notes

This repository contains rough notes covering essential and advanced concepts of JavaScript Events, focusing on real-world browser behavior and best practices.

## Topics Covered

### 1. Event Fundamentals
- What are events & event objects  
- Common events: `click`, `input`, `submit`, `load`  
- Event handlers vs `addEventListener`  
- Event phases: capturing → target → bubbling  

### 2. Event Propagation & Control
- Bubbling vs capturing (DOM behavior)  
- `stopPropagation()` vs `stopImmediatePropagation()`  
- `preventDefault()` use cases  
- Passive events & performance  

### 3. Event Delegation
- Why event delegation matters  
- Parent-based event handling  
- `event.target` vs `event.currentTarget`  
- Examples: lists, tables, modals  

### 4. Custom & Synthetic Events
- Creating events using `CustomEvent`  
- Dispatching & listening to custom events  
- Component communication  
- Decoupling logic with events  

### 5. Keyboard, Mouse & Touch Events
- Keyboard events & accessibility  
- Mouse vs pointer events  
- Touch events for mobile  
- Multi-input device handling  

### 6. Form & Input Events
- `change`, `input`, `focus`, `blur`  
- Event-based validation  
- Debouncing & throttling  
- Real-time user feedback  

### 7. Async Events & Timers
- `setTimeout` / `setInterval` as event sources  
- Promises & `async/await` with events  
- Race conditions  
- Cleanup & memory leak prevention  

📌 Note:  
These are rough learning notes pushed for understanding and revision purposes.
