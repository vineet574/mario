import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.awt.event.KeyEvent;
import java.awt.event.KeyListener;

public class SimplePlatformer extends JPanel implements ActionListener, KeyListener {
    private Timer timer;
    private int x = 50, y = 200;
    private int velocityY = 0;
    private boolean isJumping = false;

    public SimplePlatformer() {
        timer = new Timer(20, this);
        timer.start();
        addKeyListener(this);
        setFocusable(true);
        setFocusTraversalKeysEnabled(false);
    }

    @Override
    public void paintComponent(Graphics g) {
        super.paintComponent(g);
        setBackground(Color.CYAN);
        g.setColor(Color.GREEN);
        g.fillRect(0, 250, 400, 50);
        g.setColor(Color.RED);
        g.fillRect(x, y, 30, 30);
    }

    @Override
    public void actionPerformed(ActionEvent e) {
        if (y < 200) {
            velocityY += 1;
        } else {
            isJumping = false;
            velocityY = 0;
        }

        y += velocityY;

        if (y > 200) y = 200;
        repaint();
    }

    @Override
    public void keyPressed(KeyEvent e) {
        if (e.getKeyCode() == KeyEvent.VK_SPACE && !isJumping) {
            isJumping = true;
            velocityY = -15;
        }
    }

    @Override
    public void keyReleased(KeyEvent e) {}

    @Override
    public void keyTyped(KeyEvent e) {}

    public static void main(String[] args) {
        JFrame frame = new JFrame("Simple Platformer");
        SimplePlatformer platformer = new SimplePlatformer();
        frame.add(platformer);
        frame.setSize(400, 300);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        frame.setVisible(true);
    }
}
