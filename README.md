Web components consisit of folloeing sub components:-

1. Custom HTML Element
2. Shadow DOM
3. Templates and slots
4. HTML Imports



Web Component Lifecycle :-

Element Created ( in memory creation only ) ---> constructor() (Basic initializations Wrong place for accessing the dom.Custom element no added yet.)

Element Attached to DOM ---> connectedCallbak()  (DOM initializations)

Element detached from DOM ---> disconnectedCallback()  (Cleanup work)

Observed Attribute updated ---> attributeChangedCallback() (Update Data + DOM)

