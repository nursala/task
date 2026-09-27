# MetroBakery Dashboard
**HTML · CSS · Bootstrap 5.3**

A responsive bakery operations dashboard UI exercise. The page presents revenue, active ovens, staff counts, and branch status using sample data.

## Interface
- Summary cards with CSS bar charts and weekly comparisons.
- Desktop sidebar and a mobile off-canvas menu.
- Branch status table with text, color, and shape indicators.
- Bootstrap tooltips and custom styling.

## Preview locally
Clone the repository and open `index.html` in a browser, or serve the repository with Python:

```bash
git clone https://github.com/nursala/task.git
cd task
python -m http.server 8000
```

Open **http://localhost:8000**. Internet access is needed to load Bootstrap from its CDN.

## Files
| File | Responsibility |
| --- | --- |
| [index.html](index.html) | Page structure, sample content, Bootstrap components |
| [styles.css](styles.css) | Custom visual and responsive styles |

## Scope
Static frontend prototype. Metrics and dates are illustrative; navigation placeholders do not connect to an application backend. No live orders, authentication, inventory service, or database is included.
