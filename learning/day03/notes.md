# Day 03 - Tables & Forms

## HTML Tables

### Purpose

Used to display structured data in rows and columns.

### Tags

| Tag | Purpose |
|------|---------|
| `<table>` | Creates a table |
| `<tr>` | Table row |
| `<th>` | Header cell |
| `<td>` | Data cell |

### Example

```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Prince</td>
        <td>22</td>
    </tr>
</table>
```

### `colspan`

Merges multiple columns into one cell.

```html
<td colspan="2">Merged Cell</td>
```

### `rowspan`

Merges multiple rows into one cell.

```html
<td rowspan="2">Prince</td>
```

> Note: `border`, `cellpadding`, and `cellspacing` are older HTML attributes. Modern websites use CSS for table styling.

---

## HTML Forms

### Purpose

Forms are used to collect user input.

### Form Tag

```html
<form></form>
```

### Common Input Types

- text
- password
- email
- number
- date
- radio
- checkbox
- file
- submit
- reset

### Textarea

```html
<textarea></textarea>
```

### Select

```html
<select>
    <option>India</option>
</select>
```

### Important Attributes

- placeholder
- required
- name
- value

### Why Labels Matter

- Improves accessibility
- Makes forms easier to understand
- Can be linked to inputs using the `for` attribute

---

## Revision Questions

1. What is the difference between `<th>` and `<td>`?
2. What does `<tr>` represent?
3. What is the purpose of `colspan`?
4. What is the purpose of `rowspan`?
5. What is a form used for?
6. Why should radio buttons share the same `name`?
7. What is the difference between radio buttons and checkboxes?
8. When would you use a `<textarea>` instead of an `<input>`?
9. What is the purpose of the `required` attribute?