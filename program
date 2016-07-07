import UIKit

class ViewController: UIViewController {

    @IBOutlet var Textfield: UITextField!
    
    @IBOutlet var Result: UILabel!
    
    @IBAction func Guess(sender: AnyObject) {
        
        let random = String(arc4random_uniform(10))
        //if Textfield.text.isEmpty
    
        print(random)
        
        if random == Textfield.text
        {
            Result.text = "Great! Correct Number"
        }
        else
        {
            Result.text = "Wrong Number, Try Again"
        }
        
    }
    
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
    }

    override func didReceiveMemoryWarning() {
        super.didReceiveMemoryWarning()
        // Dispose of any resources that can be recreated.
    }


}

