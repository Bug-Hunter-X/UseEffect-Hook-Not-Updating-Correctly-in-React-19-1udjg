# React 19 useEffect Bug

This repository demonstrates a common issue encountered in React 19 involving the `useEffect` hook. The issue occurs when the `useEffect` hook's dependency array is not correctly defined, leading to unexpected behavior.

## Bug Description

The `useEffect` hook is intended to perform side effects after every render. However, if the dependency array is not correctly defined, the effect may not execute as expected.

## Solution

The solution involves adding the state variable to the dependency array. This ensures that the effect runs whenever the state variable changes.