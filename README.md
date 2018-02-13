# SynapsePM
SynapsePM for PMMP

* SynapsePM connects to Nemisys but players can't join.

[✔] SPP 9

[✔] Connect to Proxy

[x] PlayerJoin

## Need Help: create Pull Requests if you can :)

### Error:
```
logged out due to Login timeout
```

## API:

If you want to get synapse for given player use synapse\Player::getSynapse():
```
$synapse = $player->getSynapse();
```

Also you can get list of all synapse clients using synapsepm\SynapsePM::getSynapses():

```
$synapses = $this->getServer()->getPlugin('SynapsePM')->getSynapses();
```
