using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;

public class movescene : MonoBehaviour
{
    public void ChangeSceneBtn()
    {
        switch (this.gameObject.name)
        {
            case "ButtonName":
                SceneManager.LoadScene("SceneName");
                break;
        }
    }
}
