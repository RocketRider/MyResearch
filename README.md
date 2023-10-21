[ResearchGate Profile - Michael Möbius](https://www.researchgate.net/profile/Michael-Moebius-3)
# Summarization
The discussed papers showcase the use of artificial intelligence (AI) in military simulations and decision-making. They propose integrating AI to generate realistic tactical behavior, with AI providing strategies and orders to ground combat units while communicating with human operators through natural language. The studies demonstrate the training of reinforcement learning (RL) agents to act as battalion commanders, issuing orders and requesting fire support, and competing against each other to enhance their strategies. Additionally, the papers present the application of a commercial off-the-shelf quadcopter for autonomous surveillance, detecting and tracking objects in a monitored area. The integration of AI and advancements in technology is emphasized, as it is expected to have a significant impact on military operations and accelerate decision-making processes.

# 2023: [UPCOMING] WinterSim - Incorporation of Military Doctrines and Objectives into an ai Agent via Natural Language and Reward in Reinforcement Learning
This paper emphasizes the integration of sound tactical behavior in the generation of realistic military simulations, which includes the definition of combat tactics, doctrine, rules of engagement, and concepts of operations. Recent advances in reinforcement learning (RL) enable RL agents to generate a wide range of tactical actions. A multi-agent ground combat scenario is used in this paper to demonstrate how a machine learning (ML) application generates strategies and issues commands while following a given objective. Natural language is used to issue doctrines and objectives to improve communication between the human advisor and the ML agent. This allows us to embed objectives and existing doctrines into the reasoning of an artificial intelligence (AI). The research demonstrates the successful integration of natural language to enable an agent to achieve different objectives. This groundwork will enhance RL agents' ability in the future to uphold the doctrines and rules of military operations.
Will be presented at the WinterSim 2023 in december: https://meetings.informs.org/wordpress/wsc2023/

# 2023: [UPCOMING] NMSG Symposium ‘Simulation: Going Beyond the Limitations of the Real World’ (MSG-207)
Invited Presentation - Natural language AI for military decision support and swarm  control for autonomous UAS trained in a combat simulation
https://events.sto.nato.int/index.php/upcoming-events/event-list/event/17-symposium/520-nmsg-symposium-simulation-going-beyond-the-limitations-of-the-real-world-msg-207

# 2022: WinterSim - AI-based Military Decision Support Using Natural Language
To mimic a realistic representation of military operations, serious combat simulations require sound tactical behavior from modeled entities. Therefore, one must define combat tactics, doctrines, rules of engagement, and concepts of operation. Reinforcement learning has been proven to generate a broad range of tactical actions within the behavioral boundaries of the involved entities. In a multi-agent ground combat scenario, this paper demonstrates how our artificial intelligence (AI) application develops strategies and provides orders to subsidiary units while conducting missions accordingly. We propose a combined approach where human knowledge and responsibility collaborate with an AI system. To communicate on a common level, the orders and actions imposed by AI are given in natural language. This empowers the human operator to act in a human-on-the-loop role in order to validate and evaluate the reasoning of AI. This paper showcases the successful integration of natural language into the reinforcement learning process.
https://informs-sim.org/wsc22papers/207.pdf

# 2021: From the Game Map to the Battlefield – Using DeepMind's Advanced AlphaStar Techniques to Support Military Decision-Makers
Future warfare scenarios featuring fully digital, AI-assisted command and control and the use of unmanned systems will have a dramatic impact on the tempo of combat operations. Consequently, they will put the cycles of military decision-making under even higher time pressure. Modelling and simulation in combination with advanced AI techniques will become key enablers for future decision-support systems. These systems will support military decision-makers in the assessment of threats as well as in developing and evaluating the best possible courses of action for their own forces. The latest developments by AI research companies in the civilian domain, such as DeepMind's AlphaStar, have applied advanced deep reinforcement learning techniques to popular games like StarCraft II to train RL agents to develop superior strategies for beating their opponents.
This paper presents the results of a study conducted by the Army Concepts and Capabilities Development Centre and Airbus. The aim of the study was to evaluate how the aforementioned machine-learning techniques can be adapted and employed to train an RL agent capable of acting as a battalion commander in a combat simulation (“ReLeGSim”). In each time step of this simulation, the RL agent can send orders to the available units/companies or request multi-domain fire support. The “ReLeGSim” simulates the behaviour and combat attrition of each company/unit and fire support element at the level of the individual platform. It then returns feedback (so-called reward) to the RL agent in order to assess and improve its behaviour during the training cycle. It is also possible to select multiple trained RL agents and let them play against each other in a league system to further improve them.
Having undergone such training, the RL agent can be applied to an actual scenario. The resulting strategies can be proposed to the battalion commander as possible courses of action in a decision cycle.
https://www.sto.nato.int/publications/STO%20Meeting%20Proceedings/STO-MP-MSG-184/MP-MSG-184-14.pdf

# 2020: Der Führungsprozess von morgen – Wie Künstliche Intelligenz den Führungsprozess beschleunigen kann
Obwohl bereits in den 1950er-Jahren geprägt, kann der Begriff der Künstlichen Intelligenz (KI) auch heute noch immer missverstanden werden. Mutet er doch an, dass KI-Systeme, dem Menschen ähnlich, eigenständig abwägen, argumentieren oder gar Entscheidungen treffen. De facto ist dem nicht so. Die Künstliche Intelligenz ist ein wissenschaftliches Fachgebiet, bei dem ausschließlich Methoden und Verfahren der Mathematik und Informatik zum Einsatz kommen. Sie ist daher eher mit einem sehr fortschrittlichen Taschenrechner als mit tatsächlicher menschlicher Intelligenz vergleichbar.
Dennoch können KI-Systeme bereits heute Erstaunliches leisten, und es ist zu erwarten, dass die Komplexität der zu bewältigenden Aufgaben in den nächsten Jahren noch zunehmen wird. Im Zusammenspiel mit der Weiterentwicklung und Miniaturisierung von Integrierten Schaltkreisen, Sensoren, Motoren und Energieversorgungssystemen werden sich KI-Systeme in zahlreichen Bereichen des täglichen Lebens etablieren. Gleichermaßen bieten KI-Systeme erhebliches Potential zum Einsatz im militärischen Umfeld.
https://novumbellum.org/der-fuehrungsprozess-von-morgen-wie-kuenstliche-intelligenz-den-fuehrungsprozess-beschleunigen-kann/

# 2018: Entwicklung von Algorithmen zur autarken Beobachtung eines Interessenbereichs mittels einer Drohne
In dieser Arbeit wird gezeigt, dass ein COTS-Quadrocopter dazu dienen kann, einen Bereich zu überwachen. Zur Überwachung werden Fahrzeuge und Personen erkannt und die exakte Position dieser bestimmt. Die Genauigkeit hängt hierbei sehr stark von den Umgebungsbedingungen wie Höhe der Drohne, sowie der Landschaft ab. Es spielen aber auch die Genauigkeit von Kompass und GNSS eine Rolle. Die erkannten Objekte werden verfolgt und dem Benutzer auf einer Karte angezeigt. Die Steuerung der Drohne geschieht ausschließlich mit einem Smartphone/Tablet und der Fernbedienung für die Drohne. Soldaten im Feld haben keinen Zugriff auf große Rechenleistung, aus diesem Grund wird die Analyse der Daten auf dem Smartphone/Tablet durchgeführt.
Zur Analyse des Video-Streams wird Tensorflow Lite mit einem MobileNet-Modell eingesetzt. In dieser Arbeit wird erläutert, warum diese Technologie zum Einsatz kommt und wie diese integriert wird.
