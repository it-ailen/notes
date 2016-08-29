### Instance of
```go
package test
func tmp(src interface{}) {
    switch src.(type) {
    case *T:
        // Do something on type T
    default:
        // Default case to handle
    }
}
```

### Unsafe pointer, force to cast type
```go
package test
import "unsafe"
a := (*T)(unsafe.Pointer(src))
```
