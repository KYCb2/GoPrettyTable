# GoPrettyTable
GoPrettyTable that simple golang library for pretty data visualizing like *Python* library "*prettytable*" 

# Import
```import "github.com/KYCb2/GoPrettyTable"```

# TYPES

```golang
type Table struct {
 Fields    [][]string // Fields of table
 Delimeter rune       // Column and Row Delimeter symbol of table
}
```

# FUNCTIONS

```golang
func NewTable(del rune) (t *Table) 
// Returns New Table Object
```

# METHODS

```golang
func (t *Table) AddField(el []string)
// Add Field to Table
```

```golang
func (t *Table) Print()
// Print Pretty Table From Your Data
```
