# me-podrian-ayudar
Que rellene un array con los 20 primeros números pares y muestre su suma



package v2;
import java.util.ArrayList;
import java.util.Arrays;
import java.util.Collections;
import java.util.List;

import javax.swing.JOptionPane;

import java.util.ArrayList;
public class v2 {


	private static void printf(String string, int sum) {
		// TODO Auto-generated method stub
		int x,cont,sum,i,tabla[20];
		i=0;sum=0;
		for (x=1;x<=20;x++){cont=0;
		if (x%2==0){tabla[i]=x;i++;}}
		for (x=0;x<i;x++){sum=sum+tabla[x];
		}printf("%d\n",sum);
		JOptionPane.showMessageDialog(null, Arrays.toString(x));
		

		
	}

		
	}
	}

}
