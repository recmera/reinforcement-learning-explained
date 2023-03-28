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
