# Ghost-Push-Background-Delivery-via-Expired-APNs-Tokens
This repo documents a flaw where APNs delivered push notifications using a cached, expired token—despite failed token lookups and no app re-registration. Background daemons processed the message without an active app context, enabling covert push behavior and violating expected token lifecycle rules.
