---
layout: default
title: Send form inputs
permalink: /send/send-form-input-fields/
nav_order: 172
indent: true
---

# Send form inputs

**Status: Early design exploration**

## Address

{% include picture.html
	image = "/assets/images/send/send-inputs-address.png"
	retina = "/assets/images/send/send-inputs-address@2x.png"
	big = "/assets/images/send/send-inputs-address-big.png"
	alt-text = "List of the amount input field in different states."
	width = 800
	height = 815
%}


## Amount

{% include picture.html
	image = "/assets/images/send/send-inputs-amount.png"
	retina = "/assets/images/send/send-inputs-amount@2x.png"
	big = "/assets/images/send/send-inputs-amount-big.png"
	alt-text = "List of the address input field in different states."
	width = 800
	height = 627
%}

## Note to self

The note to self is recommended for each transaction. It can have up to 255 characters, as recommended in [BIP-329](https://github.com/bitcoin/bips/blob/master/bip-0329.mediawiki). 

{% include picture.html
	image = "/assets/images/send/send-inputs-note.png"
	retina = "/assets/images/send/send-inputs-note@2x.png"
	big = "/assets/images/send/send-inputs-note-big.png"
	alt-text = "List of the note to self input field in different states."
	width = 800
	height = 418
%}

## Fee selection

By default the application lets users choose between three standard fee options which are based on different confirmation speeds. 

### Standard fee
{% include picture.html
	image = "/assets/images/send/send-inputs-fee-standard.png"
	retina = "/assets/images/send/send-inputs-fee-standard@2x.png"
	big = "/assets/images/send/send-inputs-fee-standard-big.png"
	alt-text = "List of the fee selection input field in different states."
	width = 800
	height = 507
%}

### Custom fees

Users can set a custom fee by enabling the custom fee option in the send options dropdown. The default value is set to the same value as the default option in the standard selection.

{% include picture.html
	image = "/assets/images/send/send-form-custom-fee.png"
	retina = "/assets/images/send/send-form-custom-fee@2x.png"
	big = "/assets/images/send/send-form-custom-fee-big.png"
	alt-text = "List of the custom fee input field in different states."
	width = 800
	height = 366
%}

Users can run into special scenarios when setting a custom fee. They could, for example, try to enter a very low or extremely high. In both cases, the application shows a warning message to help users make an informed decision. 

{% include picture.html
	image = "/assets/images/send/send-inputs-fee-custom.png"
	retina = "/assets/images/send/send-inputs-fee-custom@2x.png"
	big = "/assets/images/send/send-inputs-fee-custom-big.png"
	alt-text = "List of the custom fee input field in different states."
	width = 800
	height = 718
%}
