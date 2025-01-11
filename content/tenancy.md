# What is **Tenancy**?

In the context of AWS and cloud computing, tenancy refers to how the underlying hardware resources are shared or allocated for your workloads. Think of it as deciding how you "rent" or "occupy" a physical or virtual space in a cloud environment.

### 🏠 Analogy: Renting an Apartment

Imagine you're renting a place to live. Depending on your preferences, you can:

1. **Shared Apartment (Shared Tenancy)**:
    You share the apartment with others. You have your own room, but the kitchen, living room, and other facilities are shared.
    Cloud equivalent: Your virtual machine (VM) runs on a physical server that is shared with other customers. AWS manages the sharing so you don't notice others, but you're still on the same hardware.

2. **Private Apartment (Dedicated Tenancy)**:
    You rent the entire apartment just for yourself. You don't share anything with others.
    Cloud equivalent: Your workloads run on a physical server dedicated to you. No other AWS customers can use that server.

3. **Custom-Built Home (Bare Metal or On-Premises)**:
    You design and build your own house from scratch. You have full control over everything.
    Cloud equivalent: You rent a bare-metal server (or use your own on-premises hardware) where you control every layer of the stack.

## 🛠️ Tenancy Options in AWS

AWS offers several tenancy models, depending on your needs:

### Shared Tenancy (Default)
* Description: Your instances run on shared hardware. AWS isolates your environment securely from others.
Use Case: Cost-effective and suitable for most workloads.
* Example: Running a small web app with EC2 instances.

### Dedicated Instances
* Description: Your instances run on hardware dedicated to you, but AWS still manages the hardware.
* Use Case: Compliance requirements (e.g., specific regulations for data isolation).
* Example: A financial institution needing strict data isolation.

### Dedicated Hosts
* Description: You rent an entire physical server, giving you more control over instance placement and licensing.
* Use Case: When you need to bring your own software licenses (e.g., Microsoft Windows Server).
* Example: Running a large database system with specific licensing terms.

## 📚 Real-Life Example

* **Shared Tenancy:**
    Like using a coworking space for your business. You pay less, and the workspace is shared with others, but everyone respects boundaries.

* **Dedicated Tenancy:**
    Like renting an office exclusively for your business. It costs more, but you have full control and privacy.

## 🔑 Key Points to Remember

* **Cost**: Shared tenancy is cheaper, while dedicated options are more expensive.
* **Compliance**: Dedicated tenancy may be required for industries like healthcare or finance due to strict regulations.
* **Performance**: Shared tenancy is sufficient for most workloads, but dedicated tenancy might offer more consistent performance for critical systems.


