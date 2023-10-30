## DAY-3 notes

```
 cover topcixs

* ssh-kegen --> to lgogin tito compute
* autosvallig
   * unmanaged isntance group
   ( managed instance group ( satae less0
  * managed instance group (statefull)

* clouds shelll

```


### unmanagd instnce group

*  it is manaul scalling.
*  There is not autoscallign polices

### managed instance group(state less)
```
In Google Cloud, managed instance groups (MIGs) are a way to manage groups of virtual machine instances.
Managed Instance Group Stateless:
```

* Stateless MIGs are used for workloads where each instance is independent and __doesn't store any critical data locally__.
Instances in a stateless MIG can be freely added or removed without concern for data consistency.
They are typically used for stateless applications, web servers, and other workloads where you can scale horizontally and replicate instances as needed.


### managed isnt

```


Managed Instance Group Stateful:

Stateful MIGs are designed for workloads that require some form of data persistence or state to be maintained across instance updates or replacements.
Instances in a stateful MIG maintain some form of state or data that needs to be preserved, such as databases, in-memory caches, or application-specific state.
Google Cloud's stateful MIGs are built to handle the complexities of stateful applications, ensuring that data is retained when instances are replaced or updated.

```
