# database:log:poll
वॉचडॉगला मत द्या आणि नवीन लॉग नोंदी प्रत्येक x सेकंद प्रिंट करा

**वापर:**
```
drupal database:log:poll [arguments] [options]
dblp
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--type | विशिष्ट प्रकाराद्वारे इव्हेंट फिल्टर करा.
--severity | एका विशिष्ट स्तर तीव्रतेने इव्हेंट फिल्टर करा.
--user-id | विशिष्ट वापरकर्ता आयडी द्वारे इव्हेंट फिल्टर करा.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
duration | सेकंदात जेथून डेटाबेस वाचणे दरम्यान झोपण्याची कालावधी.

## उदाहरणे
* प्रत्येक x सेकंद स्क्रीनवर लॉग प्रविष्टी मुद्रित करा
```
drupal database:log:poll \
  100
```
