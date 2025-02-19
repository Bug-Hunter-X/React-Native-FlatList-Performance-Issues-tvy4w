# React Native FlatList Performance Issues

This repository demonstrates a common performance issue in React Native when using the FlatList component with large datasets. The provided code reproduces the problem and offers a solution using optimized rendering techniques. 

## Problem

Rendering a large number of items in a FlatList without optimization can lead to poor performance, including slow rendering and potential crashes. 

## Solution

The solution provided leverages techniques like `keyExtractor`, `ItemSeparatorComponent`, `getItemLayout`, and potentially `windowSize` to improve rendering performance.  Consider also using techniques like virtualization and pagination if the data set is extremely large.