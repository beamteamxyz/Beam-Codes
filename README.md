# Beam-Codes
Platform for managing linked content behind QR and other visual codes.

Today, the purpose of Beam codes are to help consumers manage QR codes that are permanently imprinted onto their clothing and accessories such as t-shirts, hats, collars, nipple pasties and more. Because the imprinted codes are permanent, consumers need an easy self-managed tool to continually update the linked content behind their code.

Examples of linked content could include a TikTok, CashApp, Instagram, PayPal, YouTube or other internet service, or a hosted file such as a Contact Card (vCard) or other file types.


-- General Workflow:

A QR code is created and linked to a randomly generated Beam code address.
Exmple: beam.codes/dZ6efp

On first visit, the user is redirected to the admin page of said Beam code.
Example: beam.codes/dZ6efp/admin

On first visit of the admin page, the user is forced to create a numeric pin to access the page in the future.

Once a pin is created, the user will be presented with a list of options to redirect the Beam code (beam.codes/dZ6efp) to when scanned again.

On preceding vists to the admin page, the user must enter the pin, and then may select a new redirect from the pre-templated list.

The pre-templated list will include the expandable buttons which allow for the user to populate a handle (username) for the given website.
Example: Selecting "Link to Twitter" deselects any other buttons, and expands the Link to Twitter button to include a text field, whose text-entry is then augmented onto the URL path applied to the Beam code's redirect.


-- Notes

1. Limiting the set of buttons / destinations that can be linked to is intentional to control the user's onboarding experience. This is subject to change at the market acquires a general understaning of the platform.

2. Redirect paths for the Beam code should be updated as the user selects, and enters text into the button's exposed text field. (No publish or submit button should be required)
