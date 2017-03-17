A collection of convenience scripts I use for interacting with AWS ec2.

Example usage:
```bash
instance_id=$(./get_instance_by_name "my_instance")
./modify_instance_type $instance_id "c4.xlarge"
./start_instance $instance_id
```
