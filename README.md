# Generate VM Config

## Setup

Download the ArchLinux and AlmaLinux cloud images, and put them in `./images/arch.qcow2` and `./images/alma.qcow2`

## Usage

Run:
`./generate-vm --name myvm --user dev --size 64G --os alma`

This will generate a bash script that can be run to create the VM
