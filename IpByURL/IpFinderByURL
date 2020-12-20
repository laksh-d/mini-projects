package com.miniProject.programs;

import java.net.InetAddress;
import java.net.URL;

public class IpFinderByURL {

	public static void main(String[] args) {

		String url = "https://www.google.com/";

		try {
			InetAddress ip = InetAddress.getByName(new URL(url).getHost());
			System.out.println("Hostname/IP address : " + ip);
		} catch (Exception e) {
			e.printStackTrace();
		}

	}

}
