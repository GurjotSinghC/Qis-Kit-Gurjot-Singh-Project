# ***Qis-Kit-Gurjot-Singh-Project***
learning about using Quantum processors through IBM cloud using the actual quantum computers and not simulation

Inspirational quote:
> I never think of the future, It comes soon enough - Albert Einstein

## **Goals of Project**:
For my quantum computing class we have covered the key ideas behind quantum super position states and how these states can be represeted by bra-ket notation. This model is extremely useful for solving on paper but I want to learn what this entails for real quantum computing software I can run.

## ** Where will I find a Quantum Computer **:
My is answer to this is IBM cloud which actaully allows **FREE** usage of its quantum computers through the creation of an api key.

## ** Initial simulation work shown in CoLab**
The first project I am working on is to first model the superposition state of a coin using a superpsotiion of two states we can state as either heads or tails. By usitlizing the IBM runservice we can issue commands to complete physical computaiton on the IBM quantum processing unit. 

```python
import qiskit
from qiskit_ibm_runtime import QiskitRuntimeService, Sampler, Estimator, Session, Options
QiskitRuntimeService.save_account(token ="Your APi key should go here")
service = QiskitRuntimeService()
print(service.active_account)
```


$$ |\psi\rangle = \frac{1}{\sqrt{2}} |H\rangle + \frac{1}{\sqrt{2}} |T\rangle $$




