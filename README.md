# HodgePodge

![Current Form](images/current-form.jpg?raw=true "Current Form")

A keyboard, built using things I had lying around, for example a NRF52840-DK devcard, ec11 encoder, some weird display from AliExpress and a bunch of switches/diodes etc.
I also managed to get an old 3d printer (an ultimaker 2+) going with Klipper to print the parts.

- PS. It was hard to find good 2.85mm filament these days!p
- PS2. The screen is either broken or its a skill issue on my part, so will probably scrap that "tower" in the middle and go wireless split with a dongle instead
- PS3. Learning fusion as well so see the files in the 3d-files folder for what it is!

Was initially inspired by this beautiful keyboard: https://github.com/sevmeyer/chrumm-keyboard

And countless others of course, skeletyl, dactyl, cosmos, the corne I have been using for a year etc...

Wanted to experiment with some different placements for the thumb buttons and some more splay etc measured after my own fingers,
and also make the switchplate separately so I can keep experimenting without having to resolder, just build a new case or something where the plates fits, and move them there.

## Process notes

Started with testing things out on a cardboard with some old switches by just pressing them in.
Then designed the layout with <https://editor.keyboard-tools.xyz> - 
[My layout url](https://editor.keyboard-tools.xyz/#share=NobwRAhgrgLgFgewE5gFxgNIEsC2ACAMSQgDsBnHUsAGjACMIBjAa0YQBtk0wBiAMz4BTQXTo0wJCDkHcAEggAmAc0EAFRSvHEFWLNwCMABnFkADkywklAfQAeafQE5aZi1esBPB44C+1UGAoqABMtEj2qADMAHQArMH6ABwALADswcGxAGyRsan6mWFeIdGJwTmphqmxiVmOwcnOYBEAtIbRjp1dncFV1enJtMUtwR3d3UmpvrQA6mAAuv7gre3jXb2p1WVZQ2gt+tGGRpGGwY7xyYaJifWxgvvJfmAAygtLzXura-V9NeVPAA03gEgjtAhFUh1TllgokimhYtEwa1kkjkllKrFdqgWojLoZYk4ngBRYHLPaorLozFPAAiZI+OMp1IJTwAwgygk1wmhUYSKvCotF9Ccbk1hpEngAlBkkNAwJBQQRPAjAsAANU5DkiYQieMckSpZU6qUS+mSsW5xRisUNwUijmStTSBMaOsZBySN30PtOjkMhip6XucLAw1G3ymsNSWSMj1oABUGRFPddHD6jGcA0HgiHsZ7M-bTujMvpsnd9rEngBxZMOYVpjN+7NpXMtUPFRzRGOdGGxjFHSKm+5lp4AIS1qDLut5wuSlyLZ3KkXnWMCxURuUtsNOm2SPsua9aMX3KXn6KuK9hebDewOAYfAd6WRqNUDTwAggAZJOLEFoYJUloCIvnSB0siOf1InteJsX2btsmpU0zXSVIHSAsA4HrKsXHMRgZD-cAggdYD63qCDMl6AkywNWI12GdoxUMaDY0SQx6gtd9aDZABZelCMCNBclDHkSlhSJ9FNQUTxFWp3VaUJbxxSVaGJZ4OQEpBrWFHI5NInF9DglSwAARU5bT90iPTGRGODgieBMPwnTTtP0XScn0-Y7M-cyhOiSzrIUuD9CeZ5ZAASQIX93i0vy3KsjybMMpT9ieAAtSdbPBBw8VNMtANSZJDSKwVRm2IcqhqOoGiaVpIXqBoA0JSIHSHLJEnucU9gjb500SKYngAeTrHF6oyfFmtamMOpaLqDMOY4-QuK4bkyEd4zAL8RpaMbGuolqDWmzqngAPkysFRJ9Q5HDQ9JBURZE-KpAdYkfN6Oz2PEmqJWhwpGmJnsxN7H0SJ4MH+tEXuBh9QdoAAeTLuRTVEnUNd1YqFEUrk6TzkolJ4AFVtuSuVUAVJUngAKWJp4eMykUZynG1A1ySSnySNcMZtO0HSdINXQNXHDmBn1G0HOyxnGKN+tjQwNoATWJ4W3tF71xaUgtTkXEtCXLEccLAWQleh1X03VztuzqRw+zcyoRWHSsngAOXpznkdKOibrqSo0KyC6N2iLd6jYgr93NAlPK+cYXzNbIAww4Z72B59XzYrJ2QTKUts07qMNaA4TXta3IOYk48bvBDAeQyTAPQ2gsKnOInlcfDMpImyI3KU54m+iCjkUhjSk6ZjyiSdiGle9PVKd6L-2UmpGbc7s3LKRSuf82TEpTIzx2eVRfMx9z3Xx2h95cvyAq3hxvNoAARg+Yni6zwyeAA1h+N4S+Tr5SkLaAAcg-k-RKicngtAWPMIAA)

Used ai03 Plate Generator (ai03 Plate Generator) to generate a plate, that I imported in to Fusion and placed the switchholder with socketholder on each "square". duplicate with joints was a great revelation to learn here!

After that I did a lot of "lofting" to get the plate and the case somewhat functional. Printed prototypes, discarded every one and finally started soldering some diodes and wires to the back of the plate and connected them to the devcard

I also tried playing with the great tool Cosmos Keyboard Generator <https://ryanis.cool/cosmos> - here are those attempts:
- [First attempt](https://ryanis.cool/cosmos/beta#cm:Cq4BCiESCRCQcSATQICoBxIGIABAgKgHEgRAgIAHOB5AgIaKwAcKEhIFEJBlIBMSAiAAEgMQsDs4CgoXEgUQkFkgExICIAASAxCwLzgJQIDwvAIKDxIFEJBNIBMSAiAAEgA4HQoPEgUQkEEgExICIAASADgxChoSBBAQIBMSBhCggAogABICEDA4MkCAhorABwoPEgsQMECugMQfSICOUjhFGABA6oWgrvBVSNzwoqABCl0KFxITEMCAAkCAgJgCSMKZoJWQvAFQQzgIChUSEBBAQICAIEjQlYDdkPUDUAtQngIKFBIQEEBAgID4AUjmmfynkAtQV1B/GAIiBBgAIABAyYv8n9BaSK2R3I3BkwYKzgEKIRIJEJAFIBNAgKgHEgYgAECAqAcSBECAgAc4HUCAhorABwoPEgUQkBEgExICIAASADgJChQSBRCQHSATEgIgABIAOApAgPC8AgoPEgUQkCkgExICIAASADgeCg8SBRCQNSATEgIgABIAODIKGhIEEBAgExIGEKCACiAAEgIQMDgxQICGisAHCjUSEggiECAgAECmicCU8N4BSIDEUxIJQJ2AvCVIgMRTEhIIEBAgIABAoov0r7D7AUiA4D84RhgBQOmFoK7wVUjc7qKYARADGIugAiIMCL4BEL4BGOgCIJIJKBQ4A4IBAQNYR2gE)
- [Second attempt](https://ryanis.cool/cosmos/beta#cm:Cp8BChUSBRCQcSATEgIgABIAOB5AgIaKwAcKGRIFEJBlIBMSAiAAEgMQsDsSBRCwayAoOAoKHhIFEJBZIBMSAiAAEgMQsC8SBRCwXyAoOAlAgPC8AgoPEgUQkE0gExICIAASADgdCg8SBRCQQSATEgIgABIAODEKGhIEEBAgExIGEKCACiAAEgIQMDgyQICGisAHGABA6oWgrvBVSNzwoqABCl0KFxITEMCAAkCAgJgCSMKZoJWQvAFQQzgIChUSEBBAQICAIEjQlYDdkPUDUAtQngIKFBIQEEBAgID4AUjmmfynkAtQV1B/GAIiBBgAIABAyYv8n9BaSK2R3I3BkwYQAxiLoAIiDAi+ARC+ARjoAiCSCSgUOAOCAQEDWEdoBA==)


I also did a lot of exploration with different SCAD variants, generators etc. Contemplating using solderless versions etc.
But.. two goals with this projects were to get better at fusion and especially getting over my fear of soldering.

PS there are some in progress images in the images folder
