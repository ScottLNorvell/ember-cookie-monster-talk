# Ember Testing

### Why it didn't work and what we did to fix it:
-
- Refactor to JS
  - because it's cathartic
- Ember.Application.create() => Ember.Application.extend()
  - show some code oldway => new way
  - why?
    - so we can explicitely start and destroy app in tests
      - tests pass (and sometimes fail) because of leaks
    - start-app.js.erb
      - allow to centralize erb, etc BONUS
      - settings in _cne.vidzSettings instead of directly on app


### End goals

- quicker upgrades (ember keeps getting faster!)
- more confidence with sweeping changes
-
