Hi! 👋

You've opened the IDE Sandbox. 🎉

The Sandbox is an environment that you can access on "readme" and "code-along" lessons in Learn. It's a great place to experiment with code when you're not working on a "lab" (labs open the IDE In Browser).

The work you do in the Sandbox will be saved from lesson to lesson, and is automatically saved on your behalf to a repository in your GitHub account called `learn-co-sandbox`.

Please DO NOT touch this repository in GitHub, as it will affect your Sandbox experience, and potentially cause your work to be out of sync.

To learn more about the Sandbox, please visit http://help.learn.co/ide-in-browser#sandbox.


Action -> Function -> Update State
Action -> Reducer -> Updated State

Reducer => reduces the state and the action into 1 updated state - combines 2 pieces of information and reducing this combination into 1 value, we'll call this function a Reducer
******************** At the CORE of REDUX is the following***************
==> An action gets sent to a reducer which then updates the state of the application
==> Reducers are pure functions (
1. always returns the same value given a specific input &
2. have no side effects - don't have any effect outside of the function. they only return a value)

1. Given the same input of the function {count: 2} & an action of {type: 'DECREASE_COUNT', i always receive the same output from that function {count: 1}
2. Has no side-effects i.e. it does not change any value defined outside of the function, it returns a new object - does not modify an excisting one 
