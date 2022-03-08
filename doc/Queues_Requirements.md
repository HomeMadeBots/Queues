# Queues requirements

## Use cases

![Use cases](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Use_Cases.puml)

## Scenarios

The configuration use cases (_Set queue size_ and _Set type of queued data_) are
not described as scenarios.

### Enqueue item

#### Nominal scenario

![Enqueue item : nominal scenario](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Enqueue_item_nominal_scenario.puml)

#### Queue is full

![Enqueue item : queue is full](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Enqueue_item_queue_is_full.puml)

### Dequeue item

#### Nominal scenario

![Dequeue item : nominal scenario](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Dequeue_item_nominal_scenario.puml)

#### Queue is empty

![Dequeue item : queue is empty](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Dequeue_item_queue_is_empty.puml)

### Get queue size

![Get queue size](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Get_queue_size.puml)

### Get number of items

![Get number of items](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Get_number_of_items.puml)
