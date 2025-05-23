---
title: CSSCounterStyleRule
slug: Web/API/CSSCounterStyleRule
page-type: web-api-interface
browser-compat: api.CSSCounterStyleRule
---

{{APIRef("CSSOM")}}

The **`CSSCounterStyleRule`** interface represents an {{CSSxRef("@counter-style")}} [at-rule](/en-US/docs/Web/CSS/CSS_syntax/At-rule).

{{InheritanceDiagram}}

## Instance properties

_This interface also inherits properties from its parent {{DOMxRef("CSSRule")}}._

- {{DOMxRef("CSSCounterStyleRule.name")}}
  - : A string that contains the serialization of the {{CSSxRef("&lt;custom-ident&gt;")}} defined as the `name` for the associated rule.
- {{DOMxRef("CSSCounterStyleRule.system")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/system", "system")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.symbols")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/symbols", "symbols")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.additiveSymbols")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/additive-symbols", "additive-symbols")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.negative")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/negative", "negative")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.prefix")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/prefix", "prefix")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.suffix")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/suffix", "suffix")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.range")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/range", "range")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.pad")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/pad", "pad")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.speakAs")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/speak-as", "speak-as")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.
- {{DOMxRef("CSSCounterStyleRule.fallback")}}
  - : A string that contains the serialization of the {{CSSxRef("@counter-style/fallback", "fallback")}} descriptor defined for the associated rule. If the descriptor was not specified in the associated rule, the attribute returns an empty string.

## Instance methods

_This interface doesn't implement any specific method but inherits methods from its parent {{DOMxRef("CSSRule")}}._

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{CSSxRef("@counter-style")}}
- [CSS counter styles](/en-US/docs/Web/CSS/CSS_counter_styles) module
- [Using CSS counters](/en-US/docs/Web/CSS/CSS_counter_styles/Using_CSS_counters) guide
