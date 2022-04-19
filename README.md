# new-

package onecom;

public class SpringBoot {
	String categories;
	String createCategories;
	String deleteCategories;
	String updateCategories;
	public String getCategories() {
		return categories;
	}
	public void setCategories(String categories) {
		this.categories = categories;
	}
	public String getCreateCategories() {
		return createCategories;
	}
	public void setCreateCategories(String createCategories) {
		this.createCategories = createCategories;
	}
	public String getDeleteCategories() {
		return deleteCategories;
	}
	public void setDeleteCategories(String deleteCategories) {
		this.deleteCategories = deleteCategories;
	}
	public String getUpdateCategories() {
		return updateCategories;
	}
	public void setUpdateCategories(String updateCategories) {
		this.updateCategories = updateCategories;
	}
	public SpringBoot(String categories, String createCategories, String deleteCategories, String updateCategories) {
		super();
		this.categories = categories;
		this.createCategories = createCategories;
		this.deleteCategories = deleteCategories;
		this.updateCategories = updateCategories;
	}
	public SpringBoot() {
		super();
		// TODO Auto-generated constructor stub
	}
	

}





package onecom;

import java.util.ArrayList;

import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class SpringBootController {
	@RequestMapping("showCategories")
}

