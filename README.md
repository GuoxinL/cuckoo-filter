# cuckoo-filter

Fork from github.com/linvon/cuckoo-filter

## Update
Add `IsFull` function
```go
func (f *Filter) IsFull() bool {
	return f.victim.used
}
```