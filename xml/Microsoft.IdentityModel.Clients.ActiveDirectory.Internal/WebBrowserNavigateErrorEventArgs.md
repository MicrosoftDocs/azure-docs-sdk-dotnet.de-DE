<Type Name="WebBrowserNavigateErrorEventArgs" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs">
  <TypeSignature Language="C#" Value="public class WebBrowserNavigateErrorEventArgs : System.ComponentModel.CancelEventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebBrowserNavigateErrorEventArgs extends System.ComponentModel.CancelEventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class WebBrowserNavigateErrorEventArgs&#xA;Inherits CancelEventArgs" />
  <TypeSignature Language="F#" Value="type WebBrowserNavigateErrorEventArgs = class&#xA;    inherit CancelEventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ComponentModel.CancelEventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a43bf-101">Stellt das Ereignis Agruments empfangen, wenn der Browser Webnavigation schlägt fehl.</span><span class="sxs-lookup"><span data-stu-id="a43bf-101">Represents the event agruments received when web browser navigation fails.</span></span>
            <span data-ttu-id="a43bf-102">Diese Klasse ist nur bei COM-Anforderungen öffentlich, aber nicht vom Entwickler verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a43bf-102">This class is public only for COM requirements, but should not be used by the developer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebBrowserNavigateErrorEventArgs (string url, string targetFrameName, int statusCode, object webBrowserActiveXInstance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, string targetFrameName, int32 statusCode, object webBrowserActiveXInstance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.#ctor(System.String,System.String,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, targetFrameName As String, statusCode As Integer, webBrowserActiveXInstance As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs : string * string * int * obj -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs (url, targetFrameName, statusCode, webBrowserActiveXInstance)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="targetFrameName" Type="System.String" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="webBrowserActiveXInstance" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="a43bf-103">die URL als Zeichenfolge, wie im Fall eines Fehlers sie ungültige Url sein könnte</span><span class="sxs-lookup"><span data-stu-id="a43bf-103">url as a string, as in case of error it could be invalid url</span></span></param>
        <param name="targetFrameName"><span data-ttu-id="a43bf-104">Name des Zielframes, die den Fehler hatte</span><span class="sxs-lookup"><span data-stu-id="a43bf-104">Name of the target frame that had the failure</span></span></param>
        <param name="statusCode"><span data-ttu-id="a43bf-105">Statuscode "Fehler"</span><span class="sxs-lookup"><span data-stu-id="a43bf-105">Error status code</span></span></param>
        <param name="webBrowserActiveXInstance"><span data-ttu-id="a43bf-106">zurück.</span><span class="sxs-lookup"><span data-stu-id="a43bf-106">return object</span></span></param>
        <summary>
            <span data-ttu-id="a43bf-107">Konstruktor</span><span class="sxs-lookup"><span data-stu-id="a43bf-107">Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public int StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.StatusCode : int" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a43bf-108">ADAL. Systemeigene hat Code für die Auslegung dieses Codes Zeichenfolge wir nicht hier, wie wir berücksichtigt werden sollten wir dafür benötigen oder nicht.</span><span class="sxs-lookup"><span data-stu-id="a43bf-108">ADAL.Native has code for interpretation of this code to string we don't do it here, as we need to come consideration should we do it or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetFrameName">
      <MemberSignature Language="C#" Value="public string TargetFrameName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetFrameName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.TargetFrameName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetFrameName As String" />
      <MemberSignature Language="F#" Value="member this.TargetFrameName : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.TargetFrameName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a43bf-109">Name des Zielframes, die den Fehler hatte</span><span class="sxs-lookup"><span data-stu-id="a43bf-109">Name of the target frame that had the failure</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a43bf-110">die URL als Zeichenfolge, wie im Fall eines Fehlers sie ungültige Url sein könnte</span><span class="sxs-lookup"><span data-stu-id="a43bf-110">url as a string, as in case of error it could be invalid url</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebBrowserActiveXInstance">
      <MemberSignature Language="C#" Value="public object WebBrowserActiveXInstance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object WebBrowserActiveXInstance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.WebBrowserActiveXInstance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebBrowserActiveXInstance As Object" />
      <MemberSignature Language="F#" Value="member this.WebBrowserActiveXInstance : obj" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.WebBrowserActiveXInstance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a43bf-111">zurück.</span><span class="sxs-lookup"><span data-stu-id="a43bf-111">return object</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>