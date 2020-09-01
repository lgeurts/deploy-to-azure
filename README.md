[![AUR](https://img.shields.io/aur/license/apt)](https://github.com/lgeurts/deply-to-azure/LICENSE.md) [![Project Status: Active](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Flgeurts%2Fdeploy-to-azure%2Fmaster%2Ftemplate.json)

***HUISMAN EQUIPMENT B.V., Schiedam, the Netherlands***

This repository contains a fully-functioning pipeline that will use a push-to-portal button to deploy a Virtual Machine

## Prerequisites

## What will this template do

This template will deploy:

- Virtual network and subnet
- Public IP address
- Network security group allowing SSH on port 22 from the Internet
- Virtual machine running CentOS

Required information:

- Azure subscription
- Resource group
- Region (auto-selected from resource group region)
- Virtual machine name
- Administrator name
- Password

                        <kbd>[WARNING]: THIS TEMPLATE IS ONLY AVAILABLE ON APPROVAL BY YOUR MANAGER!</kbd>
## Authors

The initial setup and this file was created by [Luc Geurts](https://lgeurts.github.io) and has contributions from [Paulo Schwab Rocha](https://github.com/pschwab1).

<3

***
*Tested on Windows 10 1809 and Ubuntu 18.04 LTS*
