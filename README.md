# NVIDIA Cumulus REST API exmaples
This repository contains an MVP of interaction with NVIDIA Cumulus 5.0 REST API with Ansible

## Usage
1. Install the `requirements.txt` via pip.
2. Update the `hosts` file to match your topology. So far, a single group created for all the hosts.
3. Update the `group_vars` with your credentials and desired output directiory to store the data.
4. Update the `hosts_vars` wth IP addresses per your topology.
5. Run `ansible main.yaml`.
6. Check the content of the `output` directory.

## More details
This repository supports our blog [Karneliuk.com](https://karneliuk.com). Find the corresponding blogposts explaing these files.

## Want to be Automation Expert?
[Enroll to our Zero-To-Hero Network Automation Training](https://training.karneliuk.com/forms/). Study in online groups or in a self-paced mode.

## Need Help?
[Contact us](https://karneliuk.com/contact/) with your request and we will find the most suitable solution for you.

(c)2022, Karneliuk.com