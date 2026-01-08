1. In one sentence: What does res.render(view, data) do?
= renders an EJS template adn send rusult to client.

2. What is the difference between <%= %> and <%- %>?
= <%= %> outputs escaped HTML to prevent XSS, <%- %> outputs raw HTML without escaping.

3. Where does Express look for EJS templates (folder path)?
= Express looks for EJS templates in the views/ folder.