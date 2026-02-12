# Bootstrap Registration Page

A responsive registration webpage built with Bootstrap 5, featuring a registration form, data table, image gallery, and responsive navigation.

## Instructions

Simply open `index.html` in any modern web browser to view the page.

## Features

- **Responsive Layout**: First Name and Last Name fields positioned side-by-side using Bootstrap grid
- **Form Validation**: Email and Password fields with built-in validation
- **Required Fields**: All fields are required with visual feedback
- **Terms Checkbox**: Agreement checkbox for terms and conditions
- **Submit Button**: Styled with Bootstrap's `btn-success` class
- **Live Validation**: Real-time form validation with success/error messages

- **Responsive Table**: Wrapped in `table-responsive` div for mobile compatibility
- **Sample Data**: 5 hard-coded user entries simulating submissions
- **Enhanced Readability**: 
  - Striped rows (`table-striped`)
  - Hoverable rows (`table-hover`)
  - Dark header for better contrast

- **Responsive Banner**: Full-width banner image using `img-fluid` in a fluid container
- **Circular Profile Image**: Uses Bootstrap's `rounded-circle` class
- **Responsive Buttons**:
  - Button visible on all screen sizes
  - Button hidden on small screens (visible on medium+ screens using `d-none d-md-block`)

- **Collapsible Navbar**: Transforms into hamburger menu on smaller screens
- **Navigation Links**: Home, About, and Contact sections
- **Bootstrap Styling**: Dark theme with proper utilities

## Files

```
bootstrap-assignment/
├── index.html          # Main HTML file with all components
└── README.md          # Project documentation
```

## Usage

1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
3. **Test the form** by filling in the fields and submitting
4. **Resize** your browser window to see responsive behavior
5. **Navigate** using the navbar links

## Bootstrap Classes Used

- **Layout**: `container`, `container-fluid`, `row`, `col-*`
- **Forms**: `form-control`, `form-label`, `form-check`, `needs-validation`
- **Tables**: `table`, `table-striped`, `table-hover`, `table-responsive`
- **Images**: `img-fluid`, `rounded-circle`
- **Buttons**: `btn`, `btn-success`, `btn-primary`, `btn-warning`
- **Navigation**: `navbar`, `navbar-expand-lg`, `navbar-toggler`
- **Utilities**: `d-none`, `d-md-block`, `text-center`, `mb-*`, `py-*`

## Responsive Breakpoints

- **Small screens** (< 768px): Stacked layout, hamburger menu
- **Medium screens** (≥ 768px): Side-by-side name fields, expanded navbar
- **Large screens** (≥ 992px): Full layout with all features visible

## Form Validation

The form includes client-side validation with:
- Required field checks
- Email format validation
- Visual feedback (green for valid, red for invalid)
- Prevention of empty submissions
- Success alert on valid submission

## License

This project is created for educational purposes as part of a Bootstrap assignment.

## Author

Jake

---

**Note**: This project uses placeholder images from `via.placeholder.com`. Replace these with your own images for production use.

