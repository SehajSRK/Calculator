# Calculator
calculator in java
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author admin
 */
public class CALCULATOR extends javax.swing.JFrame {
    
    String val = "";
    String temp = "0";
    int result = 0;
    char  sign='+';
    
    public CALCULATOR() {
        initComponents();
    }

    /**
     * This method is called from within the constructor to initialize the form.
     * WARNING: Do NOT modify this code. The content of this method is always
     * regenerated by the Form Editor.
     */
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        jTextField1 = new javax.swing.JTextField();
        jButton1 = new javax.swing.JButton();
        jButton2 = new javax.swing.JButton();
        jButton3 = new javax.swing.JButton();
        jButton4 = new javax.swing.JButton();
        jButton5 = new javax.swing.JButton();
        jButton6 = new javax.swing.JButton();
        jButton7 = new javax.swing.JButton();
        jButton8 = new javax.swing.JButton();
        jButton9 = new javax.swing.JButton();
        jButton10 = new javax.swing.JButton();
        jButton11 = new javax.swing.JButton();
        jButton12 = new javax.swing.JButton();
        jButton13 = new javax.swing.JButton();
        jButton14 = new javax.swing.JButton();
        jButton15 = new javax.swing.JButton();
        jButton16 = new javax.swing.JButton();
        jButton17 = new javax.swing.JButton();
        jButton18 = new javax.swing.JButton();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);
        setMinimumSize(new java.awt.Dimension(500, 500));
        setSize(new java.awt.Dimension(500, 500));
        getContentPane().setLayout(null);

        jTextField1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jTextField1ActionPerformed(evt);
            }
        });
        getContentPane().add(jTextField1);
        jTextField1.setBounds(150, 100, 260, 40);

        jButton1.setText("=");
        jButton1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton1ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton1);
        jButton1.setBounds(360, 280, 50, 23);

        jButton2.setText("1");
        jButton2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton2ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton2);
        jButton2.setBounds(160, 160, 50, 23);

        jButton3.setText("2");
        jButton3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton3ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton3);
        jButton3.setBounds(230, 160, 50, 23);

        jButton4.setText("3");
        jButton4.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton4ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton4);
        jButton4.setBounds(300, 160, 50, 23);

        jButton5.setText("/");
        jButton5.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton5ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton5);
        jButton5.setBounds(360, 160, 50, 23);

        jButton6.setText("1");
        getContentPane().add(jButton6);
        jButton6.setBounds(360, 160, 50, 23);

        jButton7.setText("4");
        jButton7.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton7ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton7);
        jButton7.setBounds(160, 200, 50, 23);

        jButton8.setText("5");
        jButton8.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton8ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton8);
        jButton8.setBounds(230, 200, 50, 23);

        jButton9.setText("6");
        jButton9.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton9ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton9);
        jButton9.setBounds(300, 200, 50, 23);

        jButton10.setText("*");
        jButton10.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton10ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton10);
        jButton10.setBounds(360, 200, 50, 23);

        jButton11.setText("7");
        jButton11.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton11ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton11);
        jButton11.setBounds(160, 240, 50, 23);

        jButton12.setText("8");
        jButton12.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton12ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton12);
        jButton12.setBounds(230, 240, 50, 23);

        jButton13.setText("9");
        jButton13.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton13ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton13);
        jButton13.setBounds(300, 240, 50, 23);

        jButton14.setText("-");
        jButton14.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton14ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton14);
        jButton14.setBounds(360, 240, 50, 23);

        jButton15.setText("+");
        jButton15.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton15ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton15);
        jButton15.setBounds(160, 280, 50, 23);

        jButton16.setText("1");
        getContentPane().add(jButton16);
        jButton16.setBounds(160, 280, 50, 23);

        jButton17.setText("0");
        jButton17.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton17ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton17);
        jButton17.setBounds(230, 280, 50, 23);

        jButton18.setText(".");
        jButton18.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton18ActionPerformed(evt);
            }
        });
        getContentPane().add(jButton18);
        jButton18.setBounds(300, 280, 50, 23);

        pack();
    }// </editor-fold>                        

    private void jTextField1ActionPerformed(java.awt.event.ActionEvent evt) {                                            
        
    }                                           

    private void jButton15ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        temp = jTextField1.getText().toString();
        val = "";
        sign='+';
        jTextField1.setText("");
    }                                         

    private void jButton18ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        
    }                                         

    private void jButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        val += "1";
        jTextField1.setText(val);
    }                                        

    private void jButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        val += "2";
        jTextField1.setText(val);
    }                                        

    private void jButton4ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        val += "3";
        jTextField1.setText(val);
    }                                        

    private void jButton7ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        val += "4";
        jTextField1.setText(val);
    }                                        

    private void jButton8ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        val += "5";
        jTextField1.setText(val);
    }                                        

    private void jButton9ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        val += "6";
        jTextField1.setText(val);
    }                                        

    private void jButton11ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        val += "7";
        jTextField1.setText(val);
    }                                         

    private void jButton12ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        val += "8";
        jTextField1.setText(val);
    }                                         

    private void jButton13ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        val += "9";
        jTextField1.setText(val);
    }                                         

    private void jButton17ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        
        val += "0";
        jTextField1.setText(val);
    }                                         

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
       result=0;
       switch(sign)
       {
           case '+':
     
                result = Integer.parseInt(temp) + Integer.parseInt(val);
                break;
           case '-':
                        
                result = Integer.parseInt(temp) - Integer.parseInt(val);
                   break;
           case '*':
                        
                result = Integer.parseInt(temp) * Integer.parseInt(val);
                   break;
           case '/':
                        
                result = Integer.parseInt(temp) / Integer.parseInt(val);
                   break;
        
       }
        jTextField1.setText(String.valueOf(result));
    }                                        

    private void jButton14ActionPerformed(java.awt.event.ActionEvent evt) {                                          
 temp = jTextField1.getText().toString();
        val = "";
        sign='-';
        jTextField1.setText("");    
    }                                         

    private void jButton10ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        temp = jTextField1.getText().toString();
        val = "";
        sign='*';
        jTextField1.setText("");
    }                                         

    private void jButton5ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        temp = jTextField1.getText().toString();
        val = "";
        sign='/';
        jTextField1.setText("");//TODO add your handling code here:
        
    }                                        

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(CALCULATOR.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(CALCULATOR.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(CALCULATOR.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(CALCULATOR.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new CALCULATOR().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JButton jButton1;
    private javax.swing.JButton jButton10;
    private javax.swing.JButton jButton11;
    private javax.swing.JButton jButton12;
    private javax.swing.JButton jButton13;
    private javax.swing.JButton jButton14;
    private javax.swing.JButton jButton15;
    private javax.swing.JButton jButton16;
    private javax.swing.JButton jButton17;
    private javax.swing.JButton jButton18;
    private javax.swing.JButton jButton2;
    private javax.swing.JButton jButton3;
    private javax.swing.JButton jButton4;
    private javax.swing.JButton jButton5;
    private javax.swing.JButton jButton6;
    private javax.swing.JButton jButton7;
    private javax.swing.JButton jButton8;
    private javax.swing.JButton jButton9;
    private javax.swing.JTextField jTextField1;
    // End of variables declaration                   
}
