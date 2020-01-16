# any_conatiner
a simple json like container, implemented as std::variant.
## depends

cpp17

[nolhmann/json](https://github.com/nlohmann/json)


## content
`encode` convert any primitive type and std container to json
`decode` decode the json to specific primitive type or std container
`any_value` a json like container, but support int as key.

