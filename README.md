Ans: JSX stands for JavaScript XML. It is a syntax extension that allows us to write HTML-like code inside JavaScript, making React component templates much easier to write and read.

Ans: Props are read-only values passed from a parent component to a child, while state is local, mutable data managed within a component that triggers a re-render when modified.

Ans: The useState hook allows functional components to create and update local state. In this project, it was used to keep track of dynamic data like cart items, UI toggles, and user inputs.

Ans: useEffect handles side effects such as data fetching. It was used to asynchronously fetch the JSON data when the component first loads without disrupting the UI rendering process.

Ans: A unique key helps React identify which items have changed, been added, or removed. This enables efficient Virtual DOM diffing so React only re-renders the modified item instead of the whole list.

Ans: Conditional rendering means showing different UI elements based on certain state or logic conditions. Example: loading ? <Spinner/> : <DataList/> (displaying a loader while fetching and switching to the list once loaded).

Ans: Data flows from parent to child via props. To pass data back, the parent sends a callback function through props, which the child component invokes when an event occurs.
