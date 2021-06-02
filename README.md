# react-native-performance-tests

## Good Resources

- [Memoize by mrousavy](https://gist.github.com/mrousavy/0de7486814c655de8a110df5cef74ddc) 
- [Performance Almanac by Kelset](https://www.notion.so/The-React-Native-Performance-Compendium-21d58f64292e4074afb73a10f760f303)
- [Performance Guide by Callstack](https://callstack.com/data/The_Ultimate_Guide_to_React_Native_Optimization_Ebook-Callstack_FINAL.pdf)
- [Extreme Optimization of AsyncStorage by Sendbird](https://medium.com/@Sendbird/extreme-optimization-of-asyncstorage-in-react-native-b2a1e0107b34)
- [Optimizing React Native by Coinbase](https://blog.coinbase.com/optimizing-react-native-7e7bf7ac3a34)
- [Tips on profiling memory by Software Mansion](https://blog.swmansion.com/hunting-js-memory-leaks-in-react-native-apps-bd73807d0fde)
- [How To Make Your React Native App More Performant?](https://aditya01.hashnode.dev/how-to-make-your-react-native-app-more-performant)


## Libraries to check out

- https://github.com/oblador/react-native-performance
- https://github.com/Kudo/react-native-js-benchmark
- https://github.com/Kudo/react-native-cli-plugin-benchmark
- https://github.com/mrousavy/react-native-mmkv/blob/master/example/src/Benchmarks.ts

### 0.63

- RN 0.63, Android on-device Pixel 3a: WatermelonDB 10,000 Records, no JSI, Hermes Off: 579ms
- RN 0.63, Android on-device Pixel 3a: WatermelonDB 10,000 Records, no JSI, Hermes On: 247ms

- RN 0.63, iPhone 11 Simulator Release Mode: WatermelonDB 10,000 Records, no JSI, Hermes Off (0.63 doesn't support Hermes) : 437ms

## 0.64

- RN 0.64, Android on-device Pixel 3a: WatermelonDB 10,000 Records, no JSI, Hermes Off: 541ms
- RN 0.64, Android on-device Pixel 3a: WatermelonDB 10,000 Records, no JSI, Hermes On: 233ms

- RN 0.64, iPhone 11 Simulator Release Mode: WatermelonDB 10,000 Records, no JSI, Hermes Off: 422ms
- RN 0.64, iPhone 11 Simulator Release Mode: WatermelonDB 10,000 Records, no JSI, Hermes On : 226ms
