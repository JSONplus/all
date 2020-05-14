# JSONplus (all)

This repository *fakes* the composition of ALL modules within JSONplus. By refering in *composer* to `jsonplus/all`, you ensure the inclusion of all JSONplus-modules. In time this method will become to big to maintain by any using developer.

You can still "micromanage" the composition of JSONplus, by requiring each module manually in the `composer.json` file.
