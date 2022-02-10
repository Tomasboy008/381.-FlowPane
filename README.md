# 381.-FlowPane
Fluxo de componentes pela tela, exemplo utilizado quando apertamos a tela e o texto se adequa a esse movimento.
INICIO
_______________________________
public class TesteFlowPane extends FlowPane {

		public TesteFlowPane() {
			Quadrado q1 = new Quadrado();
			Quadrado q2 = new Quadrado();
			Quadrado q3 = new Quadrado();
			Quadrado q4 = new Quadrado();
			Quadrado q5 = new Quadrado();
			Quadrado q6 = new Quadrado();
			Quadrado q7 = new Quadrado();
			
			setHgap(10);
			setVgap(10);
			setPadding(new Insets(10));
			
			setOrientation(Orientation.HORIZONTAL);
			setAlignment(Pos.CENTER_RIGHT);
			
			getChildren().addAll(q1, q2, q3, q4, q5, q6, q7);
		}
}
![image](https://user-images.githubusercontent.com/95525963/153510300-e08ac163-6a21-4d83-bf82-60fc0492f635.png)
