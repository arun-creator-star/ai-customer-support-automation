# Test Cases

The AI customer support automation was tested with different customer scenarios to verify AI classification and conditional routing.

| Test | Customer Problem | AI Category | Route | Result |
|---|---|---|---|---|
| 1 | Phone screen is cracked | Product | Product Team | Passed |
| 2 | Order was not delivered | Delivery | Delivery Team | Passed |
| 3 | Customer was charged twice | Payment | Payment Team | Passed |
| 4 | Customer issue was unclear | Unclear | Customer Support | Passed |

## Testing Result

All four routing categories were tested successfully.

The workflow correctly:

1. Received the customer message.
2. Sent the message to AI for classification.
3. Stored the AI results in Google Sheets.
4. Checked the category using conditional paths.
5. Routed the issue to the appropriate email destination.

## Categories Tested

- Product
- Delivery
- Payment
- Unclear

## Result

All tested routing paths worked as expected.
