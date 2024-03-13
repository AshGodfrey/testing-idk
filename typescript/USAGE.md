<!-- Start SDK Example Usage [usage] -->
```typescript
import { Speakeasybar } from "openapi";
import { MfaMethods } from "openapi/models/components";

async function run() {
    const sdk = new Speakeasybar();

    const result = await sdk.createPet({
        name: "<value>",
        mfaMethods: [MfaMethods.Five],
    });

    // Handle the result
    console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->