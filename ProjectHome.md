The project refers to the implementation part of the paper "Cost Based Query Ordering over SROIQ Ontologies" by Ilianna Kollia and Birte Glimm, which presents an approach for cost-based query planning for conjunctive queries issued over an ontology specified in the expressive Description Logic SROIQ. The costs are based on information about the instances of concepts and roles that are extracted from a model abstraction built by a (hyper)tableau
reasoner. A static and a dynamic algorithm are presented which use these costs to find (near)optimal execution orders for the atoms of a query. The dynamic algorithm is usually better than the static one in cases in which no accurate estimates regarding the number of instances of concepts or roles and the result of joins are available before the query execution procedure starts.