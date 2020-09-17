# Capacitación en Cypress

- [ ] Instalación
  - [ ] npm init 
  - [ ] npm install -D cypress 
  - [ ] `npx cypress open`
## Cypress Basics
  - [ ] ¿Por qué Cypress?
    - [ ] Desventajas de Cypress
      - [ ] No Shadow DOM "encapsulado"
      - [ ] No Safari, No IE
      - [ ] Algunos sitios lo bloquean
        - [ ] Google
      - [ ] Siempre el mismo superdominio
        - [ ] Iframes también
          - [ ] Youtube
          - [ ] Stripe
          - [ ] Oauth
## Cypress Dashboard (TEST RUNNER)
  - [ ] `cypress run` vs `cypress open`
    - [ ] Videos
  - [ ] Boton rerun   !!<--- Botón? o Button rerun
  - [ ] Selector playground
  - [ ] Click on url
  - [ ] File Open

## Cypress Basic commands
- [ ] cypress.visit
  - [ ] *Ejercicio:* Crear mi primer test y usar cypress visit para visitar el sitio web
- [ ] cy.viewport
  - [ ] *Ejercicio:* Usar cy.viewport para cambiar el ancho de la pantalla en el mismo test
- [ ] cy.title().should('include', 'Something'
  - [ ] *Ejercicio:* usar cy.title para asegurarse que tiene el valor esperado

### Querying and interacting
- [ ] cy.get
  - [ ] *Ejercicio:* Usar query.get para obtener el título (h1) de la pantalla
- [ ] cy.contain
  - [ ] *Ejercicio:* Usar cy.contain para buscar elementos en la pantalla
- [ ] type, click, check, clear, etc..
  - [ ] *Ejercicio:* usar `type` para escribir en un input
  - [ ] *Ejercicio:* usar `clear` para borrar el input
  - [ ] *Ejercicio:* usar `check` para checkear checkbox
  - [ ] *Ejercicio:* usar `uncheck` para de-seleccionar checkbox
  - [ ] *Ejercicio:* usar `click` para hacer click en un botón

- [ ]  `const element = cy.get('selector')` and `then`
  - [ ] *Ejercicio:* Usar `const element = cy.get('selector')` para cambiar el título
    - [ ] *Tip:* Puedes usar `el.text()` para settear el texto, como en jquery
  - [ ] *Ejercicio:* Usar `then` para cambiar el título
    - [ ] *Tip:* El `then` no es una promesa
  - [ ] *Ejercicio:* Crear una nueva versión del test usando `cy.as('name')` and `cy.get('@name')`

## Assertions
- [ ] Revisar la documentación de los assertions
  - [ ] Expect
  - [ ] Assert
  - [ ] Sinon
  - [ ] Should
- [ ] Asegurarse

## Ali