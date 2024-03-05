using Engine.ViewModels;
using System.Text;
using System.Windows;
using System.Windows.Controls;
using System.Windows.Data;
using System.Windows.Documents;
using System.Windows.Input;
using System.Windows.Media;
using System.Windows.Media.Imaging;
using System.Windows.Navigation;
using System.Windows.Shapes;

namespace PapayaGame;

/// <summary>
/// Interaction logic for MainWindow.xaml
/// </summary>
public partial class MainWindow : Window
{
    private GameSession _gamesession;
    public MainWindow()
    {
        InitializeComponent();
        _gamesession = new GameSession();
        DataContext = _gamesession;
    }
    private void OnClick_MoveNorth(object sender, RoutedEventArgs e)
    {
        _gamesession.MoveNorth();
    }
    private void OnClick_MoveWest(object sender, RoutedEventArgs e)
    {
        _gamesession.MoveWest();
    }
    private void OnClick_MoveEast(object sender, RoutedEventArgs e)
    {
        _gamesession.MoveEast();
    }
    private void OnClick_MoveSouth(object sender, RoutedEventArgs e)
    {
        _gamesession.MoveSouth();
    }
}
