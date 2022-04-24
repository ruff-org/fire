# State
The client side interaction both produces and mutates a state object, which allows dynamic content updates to be communicated to the back-end framework if needed. If not, the state is simply discarded when a new resource is requested and delivered.

## State Updates
The state may also be delivered (posted) back to the back end, if needed. In such cases, it is important to ensure the state has been properly validated to prevent injection and misrepresented data.