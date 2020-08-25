{"title":"Basic Usage","meta":{"title":"Basic Usage","description":"\n<p>force set type=normal while device=phone</p>\n","order":"9"},"codes":{"jsx":"import { NumberPicker, Radio } from '@alifd/next';\n\nclass Demo extends React.Component {\n    state = {\n        device: 'desktop'\n    }\n\n    handleDeviceChange = (device) => {\n        this.setState({\n            device\n        });\n    };\n\n    render() {\n        return (\n            <div>\n                <Radio.Group\n                    shape=\"button\"\n                    value={this.state.device}\n                    onChange={this.handleDeviceChange}\n                >\n                    <Radio value=\"desktop\">desktop</Radio>\n                    <Radio value=\"phone\">phone</Radio>\n                </Radio.Group>\n                <hr/>\n                <NumberPicker device={this.state.device}/>\n            </div>\n        );\n    }\n}\n\nReactDOM.render(<Demo />, mountNode);\n"},"body":"\n````jsx\nimport { NumberPicker, Radio } from '@alifd/next';\n\nclass Demo extends React.Component {\n    state = {\n        device: 'desktop'\n    }\n\n    handleDeviceChange = (device) => {\n        this.setState({\n            device\n        });\n    };\n\n    render() {\n        return (\n            <div>\n                <Radio.Group\n                    shape=\"button\"\n                    value={this.state.device}\n                    onChange={this.handleDeviceChange}\n                >\n                    <Radio value=\"desktop\">desktop</Radio>\n                    <Radio value=\"phone\">phone</Radio>\n                </Radio.Group>\n                <hr/>\n                <NumberPicker device={this.state.device}/>\n            </div>\n        );\n    }\n}\n\nReactDOM.render(<Demo />, mountNode);\n````","html":"<script>(function(){'use strict';\n\nvar _createClass = function () { function defineProperties(target, props) { for (var i = 0; i < props.length; i++) { var descriptor = props[i]; descriptor.enumerable = descriptor.enumerable || false; descriptor.configurable = true; if (\"value\" in descriptor) descriptor.writable = true; Object.defineProperty(target, descriptor.key, descriptor); } } return function (Constructor, protoProps, staticProps) { if (protoProps) defineProperties(Constructor.prototype, protoProps); if (staticProps) defineProperties(Constructor, staticProps); return Constructor; }; }();\n\nvar _next = require('@alifd/next');\n\nfunction _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError(\"Cannot call a class as a function\"); } }\n\nfunction _possibleConstructorReturn(self, call) { if (!self) { throw new ReferenceError(\"this hasn't been initialised - super() hasn't been called\"); } return call && (typeof call === \"object\" || typeof call === \"function\") ? call : self; }\n\nfunction _inherits(subClass, superClass) { if (typeof superClass !== \"function\" && superClass !== null) { throw new TypeError(\"Super expression must either be null or a function, not \" + typeof superClass); } subClass.prototype = Object.create(superClass && superClass.prototype, { constructor: { value: subClass, enumerable: false, writable: true, configurable: true } }); if (superClass) Object.setPrototypeOf ? Object.setPrototypeOf(subClass, superClass) : subClass.__proto__ = superClass; }\n\nvar Demo = function (_React$Component) {\n    _inherits(Demo, _React$Component);\n\n    function Demo() {\n        var _ref;\n\n        var _temp, _this, _ret;\n\n        _classCallCheck(this, Demo);\n\n        for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {\n            args[_key] = arguments[_key];\n        }\n\n        return _ret = (_temp = (_this = _possibleConstructorReturn(this, (_ref = Demo.__proto__ || Object.getPrototypeOf(Demo)).call.apply(_ref, [this].concat(args))), _this), _this.state = {\n            device: 'desktop'\n        }, _this.handleDeviceChange = function (device) {\n            _this.setState({\n                device: device\n            });\n        }, _temp), _possibleConstructorReturn(_this, _ret);\n    }\n\n    _createClass(Demo, [{\n        key: 'render',\n        value: function render() {\n            return React.createElement(\n                'div',\n                null,\n                React.createElement(\n                    _next.Radio.Group,\n                    {\n                        shape: 'button',\n                        value: this.state.device,\n                        onChange: this.handleDeviceChange\n                    },\n                    React.createElement(\n                        _next.Radio,\n                        { value: 'desktop' },\n                        'desktop'\n                    ),\n                    React.createElement(\n                        _next.Radio,\n                        { value: 'phone' },\n                        'phone'\n                    )\n                ),\n                React.createElement('hr', null),\n                React.createElement(_next.NumberPicker, { device: this.state.device })\n            );\n        }\n    }]);\n\n    return Demo;\n}(React.Component);\n\nReactDOM.render(React.createElement(Demo, null), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> NumberPicker<span class=\"token punctuation\">,</span> Radio <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">class</span> <span class=\"token class-name\">Demo</span> <span class=\"token keyword\">extends</span> <span class=\"token class-name\">React<span class=\"token punctuation\">.</span>Component</span> <span class=\"token punctuation\">{</span>\n    state <span class=\"token operator\">=</span> <span class=\"token punctuation\">{</span>\n        device<span class=\"token operator\">:</span> <span class=\"token string\">'desktop'</span>\n    <span class=\"token punctuation\">}</span>\n\n    <span class=\"token function-variable function\">handleDeviceChange</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token parameter\">device</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n        <span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span><span class=\"token function\">setState</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">{</span>\n            device\n        <span class=\"token punctuation\">}</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n    <span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\n    <span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token punctuation\">{</span>\n        <span class=\"token keyword\">return</span> <span class=\"token punctuation\">(</span>\n            <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Radio.Group</span></span>\n                    <span class=\"token attr-name\">shape</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>button<span class=\"token punctuation\">\"</span></span>\n                    <span class=\"token attr-name\">value</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span>state<span class=\"token punctuation\">.</span>device<span class=\"token punctuation\">}</span></span>\n                    <span class=\"token attr-name\">onChange</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span>handleDeviceChange<span class=\"token punctuation\">}</span></span>\n                <span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Radio</span></span> <span class=\"token attr-name\">value</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>desktop<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">desktop</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Radio</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Radio</span></span> <span class=\"token attr-name\">value</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>phone<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">phone</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Radio</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Radio.Group</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>hr</span><span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">NumberPicker</span></span> <span class=\"token attr-name\">device</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span>state<span class=\"token punctuation\">.</span>device<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span>\n        <span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n    <span class=\"token punctuation\">}</span>\n<span class=\"token punctuation\">}</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Demo</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}