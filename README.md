# react-practice-2022-1

Created with CodeSandbox

- TODO
- Add some tests
- Practice CSS
- How could async can be handled properly or more elegently

- thoughts about use async hook
  https://usehooks.com/useAsync/
  use async can be a custom hook, which take the aysnc function as the input, output as the status, result.

  ```js
  const [isLoading, result, errorMessage] = useAsync(asyncFun);
  ```

  it handle the async process in the hook at the time the hook is construct

  every time the Usage component need to perform async process can use the hook and then pass on the exposed state to Loader and Error components and itself for consumption
