# Vortrag zum Thema Rest in controllern

- Resource and Actions
- als erstes routes.rb öffnen, zeigt viel über die App
- Anti Pattern Complex Actions

[Vortrag RailsConf 2017: In Relentless Pursuit of REST by Derek Prior 36:18](https://www.youtube.com/watch?v=HctYHe-YjnE&ab_channel=Confreaks)


```ruby
users#edit_password
users#update_password
noun#verb_noun
```

Hier müsste es heissen. Password ist die Resource => noun. Es muss nicht unbedingt ein Model sein. Das Argument das ist keinen neuen Controller wert, ist kein gutes. Es muss nicht immer eine 1:1 Beziehung zwischen Controller und Model sein.

```ruby
passwords#edit
passwords#update
```
