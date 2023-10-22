# 代码样式指南

## HTML

### 文档结构

- 对于HTML5文档，请使用 `<!DOCTYPE html>`。
- 通过适当的缩进和换行来组织HTML代码，以增加可读性。

### 头部部分

- 在 `<title>` 元素中包含描述性标题。
- 使用 `src` 或 `href` 属性引入外部CSS和JavaScript文件。
- 将相关元素分组，以获得清晰和有序的 `<head>` 部分。

### 主体部分

- 维护清晰和逻辑的文档结构。
- 使用语义化的HTML元素，以提高可访问性。
- 使ID和类名称有意义和描述性。
- 使用CSS样式进行样式设置，避免内联样式。
- 使用JavaScript实现交互功能。

### 按钮

- 确保按钮具有清晰和描述性的标签。
- 对于带有JavaScript功能的按钮，请使用 `onclick` 调用适当的函数。
- 对于具有相应值的按钮，请使用 `value` 属性。

### CSS样式

- 使用外部CSS文件。
- 遵循一致且经过良好文档化的类和ID命名约定。
- 将相关样式分组在一起。
- 使用注释来解释特定CSS规则的目的。

- # JavaScript Code Style

## Code Structure

- Maintain a clean and organized code structure with proper indentation and line breaks.
- Use meaningful variable and function names.
- Keep related code together to enhance code readability.

## Event Handling

- Attach event handlers to elements using the `.onclick` property.
- Handle different button click events within a loop and use conditional statements to determine the action.

## Mathematical Expressions

- For mathematical expressions, provide clear and concise comments.
- Handle special functions (e.g., sin, cos, tan, lg, ln, sqrt, e, pi, abs) by replacing them with their JavaScript equivalents.
- Use the `eval` function to evaluate the expressions and handle errors gracefully.

## XMLHttpRequest

- Create and configure XMLHttpRequest objects for making asynchronous requests.
- Use the `xhr.open` method to specify the request method (e.g., POST or GET) and the URL.
- Set request headers, such as 'Content-type' for JSON data.
- Implement an `onreadystatechange` event handler to process the response.
- Send data in JSON format and handle both success and error cases.

## Theme Toggle

- Implement a theme toggle feature to switch between dark and light themes.
- Create a button to trigger the theme change.
- Update the CSS class of elements to apply the selected theme.

## Variable Naming

- Use meaningful variable names like `display`, `buttons`, `themeToggleBtn`, and `isDark`.
- Follow a consistent naming convention, such as camelCase.

## Error Handling

- Handle errors gracefully, and display meaningful error messages.
- Use try-catch blocks to capture and manage errors during evaluation.
- Provide descriptive comments for error handling.

Source: Personal code for Huihuang's Calculator.

# CSS Code Style

## Global Style Reset

- Reset external margins and paddings using `*`.
- Use the `box-sizing` property with the value `border-box` for a consistent box model.
- Remove default outlines.
- Apply a smooth transition to all properties for better user experience.

## Global Font Style

- Set the global font style to a sans-serif typeface for consistency.
- Remove underlines from links.
- Define a background image for the entire page with a gradient background color.

## Container Style

- Center-align the container content by using the CSS Grid layout.
- Set the container's height and width to fill the entire viewport.
- Ensure responsive design with auto height and width.

## Calculator Style

- Apply relative positioning to the calculator for internal element positioning.
- Add padding, border-radius, and box-shadow for aesthetic appeal.

## Theme Toggle Button Style

- Position the theme toggle button absolutely and style it.
- Include styles for the button's active state.
- Create a pseudo-element for the button.

## Display Screen Style

- Style the display screen with margins, height, width, and scroll properties.
- Customize the scrollbar style.

## Button Style

- Style buttons with specific dimensions, border radius, and typography.
- Implement a hover effect to enlarge buttons on mouseover.
- Adjust the style of the equal button.

## Day Theme Style

- Define styles for the calculator, display, and different button types for the day theme.

## Dark Theme Style

- Customize the calculator's appearance for the dark theme.
- Create styles for the calculator's display and various button types.

## History Display Style

- Apply specific styles to the history display box, including background color, border, margins, and padding.

Source: Personal code for Huihuang's Calculator.

