# OpenFlow-Controller
# PartA:
All traffic arriving on a switch will be forwarded to the controller. The controller then instructs the switch to forward the packet on all ports except the one it arrived on.
# PartB:
All traffic arriving on a switch will be forwarded to the controller. Modify the default controller so that, for each switch, it learns the mapping between MAC addresses and ports. It then instructs the switch which port to forward the packet on.
# PartC:
Now, we will try to make the switch a bit smarter. Modify the controller from Part B so that when it learns a mapping, it installs a flow rule on the switch to handle future packets. Thus, the only packets that should arrive at the controller are those that the switch doesn’t have a flow entry for.
