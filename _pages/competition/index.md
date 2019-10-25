---
layout: competition
id: competition
nav: true
nav-order: 7

title: Compet&shy;ition
long-title: Your chalet awaits – enter now to win!
intro: How does waking up to mountain views sound? With breakfast? Skis by the door and a short hop to the cable car that puts you at the heart of Verbier’s finest slopes? It sounds fantastic, of course. And it could all be yours. Enter now and win three luxurious nights at Üna Lodge, a contemporary stay in the heart of Le Châble with sauna and hot tub for those apres ski soothers. You’ll be a stones-throw from the cable car that ascends to Verbier’s best slopes, and close to a fine selection of restaurants, bars and shops. Get there with SWISS, who will fly you from London to Geneva with all your ski equipment.
short-intro: Wake up to mountain views, stay in bed, drink your coffee, grab your skis and hit the slopes. Win this unmissable ski break and this could be you, staying at the contemporary Üna Lodge with flights from SWISS.
enter-cta: Enter Now

competition-form:
  id: comp
  post-url: https://getform.io/f/0c4bee73-4490-4f4e-8190-a643fe6b896f
  expiry-date: 2020-01-01
  fields:
    - id: name
      type: text
      label: Name
      required: true
    - id: email
      type: email
      label: Email
      required: true
    - id: qualify
      type: radio
      label: Are you a UK resident and over the age of 18?
      required: true
      options:
        - id: qualify-true
          label: 'Yes'
          value: 'yes'
        - id: qualify-false
          label: 'No'
          value: 'no'
          invalid: true
    - id: opt-in
      type: radio
      label: Would you like to receive emails from Swiss International Air Lines?
      required: true
      options:
        - id: opt-in-true
          label: 'Yes'
          value: 'yes'
        - id: opt-in-false
          label: 'No'
          value: 'no'
  submit: Submit Entry
  terms: >
    By submitting your entry, you agree to the <a href="#" class="js-open-modal link--underlined" data-open-modal="competition-terms">terms and conditions</a> of this competition
---