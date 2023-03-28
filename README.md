# Theory

## Q-Learning

Q-Learning es un algoritmo de aprendizaje por refuerzo que tiene como objetivo aprender una función de valor Q, que representa el valor esperado de la recompensa acumulada para cada posible acción en un estado determinado. La idea es encontrar la política óptima, que es la secuencia de acciones que maximiza la recompensa acumulada a largo plazo.

El proceso de aprendizaje en Q-Learning implica la exploración del entorno mediante la ejecución de acciones y la observación de las recompensas asociadas a cada acción en cada estado. A partir de esta información, se actualiza el valor Q para cada par estado-acción, utilizando una ecuación de actualización basada en el error de estimación de la recompensa.

Una de las principales características de Q-Learning es que no requiere conocimiento previo del modelo del entorno, lo que lo hace útil para problemas de RL en los que el modelo del entorno es desconocido o es difícil de especificar.

Las aplicaciones de Q-Learning son diversas y van desde juegos hasta robótica y control de sistemas. Algunos ejemplos de aplicaciones incluyen:

- Juegos de tablero: Q-Learning puede utilizarse para aprender a jugar juegos de tablero como el ajedrez o el Go.
- Control de robots: Q-Learning puede utilizarse para enseñar a un robot a realizar tareas complejas en un entorno dinámico.
- Control de procesos industriales: Q-Learning puede utilizarse para controlar procesos industriales como la producción de alimentos o productos químicos.
- Gestión de recursos: Q-Learning puede utilizarse para optimizar la gestión de recursos en situaciones como el control del tráfico aéreo o la distribución de energía.

Para aplicar Q-Learning, es necesario definir el espacio de estados y acciones, así como el conjunto de recompensas. Además, es importante establecer una tasa de aprendizaje adecuada y un factor de descuento que permita equilibrar la importancia de las recompensas a corto y largo plazo. Una vez definido esto, se puede implementar el algoritmo utilizando un bucle de iteraciones en el que el agente ejecuta acciones en el entorno y actualiza su función de valor Q en función de las recompensas obtenidas. Es importante tener en cuenta que Q-Learning puede requerir un gran número de iteraciones para converger a una política óptima.

## SARSA (State-Action-Reward-State-Action)

SARSA es un algoritmo de aprendizaje por refuerzo que tiene como objetivo aprender una política óptima para un problema de decisión secuencial Markoviano. El nombre SARSA proviene de las siglas State-Action-Reward-State-Action, ya que el algoritmo actualiza su función de valor Q en función de la tupla (estado, acción, recompensa, siguiente estado, siguiente acción).


    Un problema de decisión secuencial Markoviano (MDP, por sus siglas en inglés) es un modelo matemático que describe un proceso de decisión en el que una entidad toma decisiones en un entorno incierto y dinámico, con el objetivo de maximizar una recompensa a largo plazo.

    En un MDP, las decisiones se toman en un conjunto de estados posibles, y cada estado está asociado con una probabilidad de transición a otros estados en función de las acciones tomadas. Además, cada transición está asociada con una recompensa que se recibe al llegar al nuevo estado.

    La propiedad Markoviana se refiere a la propiedad de memoria corta de los estados. Esto significa que la probabilidad de transición y la recompensa en un estado dado solo dependen del estado actual y la acción tomada, y no de los estados anteriores.

    El objetivo en un MDP es encontrar una política óptima que permita al agente tomar las mejores decisiones en cada estado para maximizar la recompensa acumulada a largo plazo. El problema se resuelve mediante el cálculo de una función de valor que asigna a cada estado una medida de la calidad de la política y que se utiliza para seleccionar las acciones óptimas en cada estado.

    El aprendizaje por refuerzo es una técnica que se utiliza para resolver problemas de decisión secuencial Markovianos, ya que permite que un agente aprenda a través de la interacción con el entorno, sin necesidad de conocer el modelo exacto del mismo. Algunos algoritmos comunes de aprendizaje por refuerzo que se utilizan para resolver MDP incluyen Q-learning, SARSA y Actor-Critic.


Al igual que Q-Learning, SARSA utiliza un proceso de iteración de valor para aprender una función de valor Q, que representa el valor esperado de la recompensa acumulada para cada posible acción en un estado determinado. Sin embargo, a diferencia de Q-Learning, SARSA utiliza una política de control suave (soft control policy) en lugar de una política de control estricta (greedy policy).

La política de control suave permite al agente explorar el entorno de manera más efectiva, lo que puede ser útil en situaciones en las que el entorno es incierto o la recompensa es rara. En cada iteración, el agente elige una acción en función de la política de control suave, y actualiza su función de valor Q en función de la recompensa obtenida y la siguiente acción elegida.

Una de las principales características de SARSA es que es un algoritmo on-policy, lo que significa que actualiza su función de valor Q en función de la política actual que está siguiendo el agente. Esto puede ser útil en situaciones en las que se requiere un equilibrio entre la exploración y la explotación del entorno.

Las aplicaciones de SARSA son diversas y van desde robótica y control de sistemas hasta juegos y aprendizaje en línea. Algunos ejemplos de aplicaciones incluyen:

- Control de robots: SARSA puede utilizarse para enseñar a un robot a realizar tareas complejas en un entorno dinámico.
- Juegos de mesa: SARSA puede utilizarse para aprender a jugar juegos de mesa como el ajedrez o el Go.
- Gestión de recursos: SARSA puede utilizarse para optimizar la gestión de recursos en situaciones como el control del tráfico aéreo o la distribución de energía.

Para aplicar SARSA, es necesario definir el espacio de estados y acciones, así como el conjunto de recompensas. Además, es importante establecer una tasa de aprendizaje adecuada y un factor de descuento que permita equilibrar la importancia de las recompensas a corto y largo plazo. Una vez definido esto, se puede implementar el algoritmo utilizando un bucle de iteraciones en el que el agente ejecuta acciones en el entorno y actualiza su función de valor Q en función de las recompensas obtenidas y las acciones seleccionadas.

## DQN (Deep Q-Network)

## Double DQN

## Dueling DQN

## REINFORCE

## Actor-Critic

## A2C (Advantage Actor-Critic)

## PPO (Proximal Policy Optimization)

## TRPO (Trust Region Policy Optimization)

## ACKTR (Actor-Critic using Kronecker-Factored Trust Region)

## DDPG (Deep Deterministic Policy Gradient)

## TD3 (Twin Delayed DDPG)

## SAC (Soft Actor-Critic)

## HER (Hindsight Experience Replay)

## Rainbow

## C51

## IQN (Implicit Quantile Network)

## IMPALA (Importance Weighted Actor-Learner Architecture)
