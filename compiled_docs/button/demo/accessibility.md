{"title":"无障碍","meta":{"title":"无障碍","description":"\n<p>在使用不包含文本的icon Button组件时，我们需要添加<code>aria-label</code>对其进行描述，键盘操作请参考<code>ARIA and KeyBoard</code>。</p>\n","order":"9"},"codes":{"jsx":"import { Button, Icon } from '@alifd/next';\n\nReactDOM.render(<div>\n    <Button.Group>\n        <Button type=\"primary\" aria-label=\"prompt button\"><Icon type=\"prompt\" /></Button>\n        <Button type=\"primary\" aria-label=\"clock button\"><Icon type=\"clock\" /></Button>\n        <Button type=\"primary\" aria-label=\"set button\"><Icon type=\"set\" /></Button>\n    </Button.Group>\n</div>, mountNode);\n"},"body":"\n\n````jsx\nimport { Button, Icon } from '@alifd/next';\n\nReactDOM.render(<div>\n    <Button.Group>\n        <Button type=\"primary\" aria-label=\"prompt button\"><Icon type=\"prompt\" /></Button>\n        <Button type=\"primary\" aria-label=\"clock button\"><Icon type=\"clock\" /></Button>\n        <Button type=\"primary\" aria-label=\"set button\"><Icon type=\"set\" /></Button>\n    </Button.Group>\n</div>, mountNode);\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nReactDOM.render(React.createElement(\n    \"div\",\n    null,\n    React.createElement(\n        _next.Button.Group,\n        null,\n        React.createElement(\n            _next.Button,\n            { type: \"primary\", \"aria-label\": \"prompt button\" },\n            React.createElement(_next.Icon, { type: \"prompt\" })\n        ),\n        React.createElement(\n            _next.Button,\n            { type: \"primary\", \"aria-label\": \"clock button\" },\n            React.createElement(_next.Icon, { type: \"clock\" })\n        ),\n        React.createElement(\n            _next.Button,\n            { type: \"primary\", \"aria-label\": \"set button\" },\n            React.createElement(_next.Icon, { type: \"set\" })\n        )\n    )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Button<span class=\"token punctuation\">,</span> Icon <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button.Group</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>prompt button<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Icon</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>prompt<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>clock button<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Icon</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>clock<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>set button<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Icon</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>set<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button.Group</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}