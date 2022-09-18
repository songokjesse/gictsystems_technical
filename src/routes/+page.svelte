<script>
import Tabs from "../lib/components/Tabs.svelte";
import AddressForm from "../lib/components/AddressForm.svelte";
import AddressBook from "../lib/components/AddressBook.svelte";
// List of tab items with labels, values and assigned components
let items = [
    { label: "Contact Form",
        value: 1,
        component: AddressForm
    },
    { label: "Address Book",
        value: 2,
        component: AddressBook
    },
];
</script>
<div class="container m-3">
    <Tabs class="mt-6" {items}/>
</div>