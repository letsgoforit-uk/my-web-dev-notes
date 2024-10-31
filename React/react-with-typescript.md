# React and Typescript

### Props

#### 1) Adding basic props

App.jsx

```
import { Greeting } from "./components/Greeting";

const App = () => {
  return (
    <div className="App">
      <Greeting name="Fred" />
    </div>
  );
};
```

components/Greeting.tsx

```
type GreetingProps = {
  name: string;
};

export const Greeting = (props: GreetingProps) => {
  return (
    <div>
      <p>Hello {props.name}</p>
    </div>
  );
};
```

#### 2) Types or Interfaces for Props?

It is suggested that you use Types for applications, and Interfaces for libraries when creating Props.
