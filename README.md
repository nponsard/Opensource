# Opensource

A list of opensource contribution made during my studies

## [openapi-fuzzer](https://github.com/matusf/openapi-fuzzer)

openapi-fuzzer is a tool to test if there's difference between the OpenApi definition and the behavior of API endpoints. I used this project to test the [nethsm](https://github.com/Nitrokey/nethsm) API in a CI. I needed the fuzzer to connect using HTTPS without checking the certificates so I modified the project to allow this and then proposed the modification on the upstream repository. This change also changed the way connections are handled, improving performances.

- State of the project : in production
- Community : not very active
- Stack : Rust, OpenApi

## [NetHSM](https://github.com/Nitrokey/nethsm)

NetHSM is a project started by Nitrokey for creating an open source Hardware Security Module accessible from the network.
During my internship I worked on the NetHSM firmware that is now open source on GitHub. I mainly worked on improving the CI and test cases.

- State of the project : in production
- Community : small, not very active
- Stack : Ocaml, MirageOS

## [nethsm-pkcs11](https://github.com/Nitrokey/nethsm-pkcs11)

This is the main project I worked on during my internship, the goal is to create a PKCS#11 module so applications implementing the PKCS#11 protocol can use a [NetHSM](https://www.nitrokey.com/products/nethsm) without needing to modify the application. I did most of the developpement and now I'm helping the team to matain the project.

- State of the project : in production
- Community : small, not very active
- Stack : Rust, C library, PKCS#11

## [discordgo](https://github.com/bwmarrin/discordgo)

Discordgo is a library for making discord bot in go. I found a small bug and decided po fix it in a pull request.

- State of the project : in production
- Community : not very active
- Stack : Go, Discord API
