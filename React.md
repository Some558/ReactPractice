## Reactの雛形
import { StrictMode } from 'react';
import { createRoot } from 'react-dom/client';
const rootElement = document.getElementById('root');
const root = createRoot(rootElement);

const App = () => {};

root.render(
  <StrictMode>
    <h1>こんにちは</h1>
    <alert>アラートです。</arelt>
  </StrictMode>
);
