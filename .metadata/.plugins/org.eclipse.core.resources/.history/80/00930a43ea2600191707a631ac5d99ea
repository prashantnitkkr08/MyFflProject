package com.restCalls.main;

import java.io.BufferedReader;
import java.io.File;
import java.io.IOException;
import java.io.InputStreamReader;
import java.util.ArrayList;
import java.util.List;

import org.springframework.stereotype.Component;

@Component
public class CallScript {

	public String callToScriptOne(String communityId,String paramOne,String versionId)
	{
		//CallLogic.shellScriptExecution();
		String result = communityId+" "+paramOne+" "+versionId;
		return result;
	}
	
	public String callToScriptTwo(String communityId,String paramOne,String versionId,String paramTwo) throws IOException, InterruptedException
	{
		//running a bat file
		//CallLogic.batFileExecution();
		String result = communityId+" "+paramOne+" "+versionId+" "+paramTwo;
		return result;
	}
	

	public String callToScriptThird(String communityId,String paramOne,String versionId,String paramTwo,String paramThree) throws IOException
	{
		//running command drom cmd
		//CallLogic.executionThroughTerminal();
		
		String result = communityId+" "+paramOne+" "+versionId+" "+paramThree;
		return result;
	}
	
	public String callToScriptFourth(String communityId,String paramOne,String versionId,String paramTwo, String paramThree,String paramFourth)
	{
		String result = communityId+" "+paramOne+" "+versionId+" "+paramThree+" "+paramFourth;
		return result;
	}
	
	public String callToScriptFifth(String communityId,String paramOne,String versionId,String paramTwo,String paramThree,String paramFourth,String paramFifth)
	{
		String result = communityId+" "+paramOne+" "+versionId+" "+paramTwo+" "+paramThree+" "+paramFourth+" "+paramFifth;
		return result;
	}
	
}
