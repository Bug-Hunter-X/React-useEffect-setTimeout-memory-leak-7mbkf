# React UseEffect setTimeout memory leak
This example demonstrates a common error in React applications: memory leaks caused by the improper use of setTimeout within the useEffect hook.  The provided solution shows how to correctly implement the timer using cleanup for better memory management and prevents the component from continuing to update even after it has unmounted.