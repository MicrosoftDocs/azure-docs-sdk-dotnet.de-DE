<Type Name="HandlerMapping" FullName="Microsoft.Azure.Management.WebSites.Models.HandlerMapping">
  <TypeSignature Language="C#" Value="public class HandlerMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HandlerMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HandlerMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class HandlerMapping" />
  <TypeSignature Language="F#" Value="type HandlerMapping = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1e991-101">Die IIS-Handlerzuordnungen verwendet, um zu definieren, welche Handler HTTP-Anforderungen mit bestimmten Erweiterung verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="1e991-101">The IIS handler mappings used to define which handler processes HTTP requests with certain extension.</span></span>
            <span data-ttu-id="1e991-102">Es wird z. B. verwendet, so konfigurieren Sie Php-cgi.exe-Prozess, um alle HTTP-Anforderungen mit der Erweiterung \*.PHP zu verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="1e991-102">For example, it is used to configure php-cgi.exe process to handle all HTTP requests with \*.php extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HandlerMapping ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HandlerMapping.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e991-103">Initialisiert eine neue Instanz der HandlerMapping-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e991-103">Initializes a new instance of the HandlerMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HandlerMapping (string extension = null, string scriptProcessor = null, string arguments = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string extension, string scriptProcessor, string arguments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HandlerMapping.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional extension As String = null, Optional scriptProcessor As String = null, Optional arguments As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HandlerMapping : string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HandlerMapping" Usage="new Microsoft.Azure.Management.WebSites.Models.HandlerMapping (extension, scriptProcessor, arguments)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="extension" Type="System.String" />
        <Parameter Name="scriptProcessor" Type="System.String" />
        <Parameter Name="arguments" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extension"><span data-ttu-id="1e991-104">Anforderungen mit dieser Erweiterung werden über die angegebene FastCGI-Anwendung behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="1e991-104">Requests with this extension will be handled using the specified FastCGI application.</span></span></param>
        <param name="scriptProcessor"><span data-ttu-id="1e991-105">Der absolute Pfad der FastCGI-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="1e991-105">The absolute path to the FastCGI application.</span></span></param>
        <param name="arguments"><span data-ttu-id="1e991-106">Befehlszeilenargumente, die an den Skriptprozessor übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="1e991-106">Command-line arguments to be passed to the script processor.</span></span></param>
        <summary>
            <span data-ttu-id="1e991-107">Initialisiert eine neue Instanz der HandlerMapping-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e991-107">Initializes a new instance of the HandlerMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public string Arguments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Arguments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HandlerMapping.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public Property Arguments As String" />
      <MemberSignature Language="F#" Value="member this.Arguments : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HandlerMapping.Arguments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="arguments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e991-108">Ruft ab, oder legt ihn fest Befehlszeilenargumente Skriptprozessor übergeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="1e991-108">Gets or sets command-line arguments to be passed to the script processor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extension">
      <MemberSignature Language="C#" Value="public string Extension { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Extension" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HandlerMapping.Extension" />
      <MemberSignature Language="VB.NET" Value="Public Property Extension As String" />
      <MemberSignature Language="F#" Value="member this.Extension : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HandlerMapping.Extension" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extension")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e991-109">Ruft ab oder legt ihn fest Anforderungen mit dieser Erweiterung behandelt, die die angegebene FastCGI-Anwendung verwenden.</span><span class="sxs-lookup"><span data-stu-id="1e991-109">Gets or sets requests with this extension will be handled using the specified FastCGI application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptProcessor">
      <MemberSignature Language="C#" Value="public string ScriptProcessor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptProcessor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HandlerMapping.ScriptProcessor" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptProcessor As String" />
      <MemberSignature Language="F#" Value="member this.ScriptProcessor : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HandlerMapping.ScriptProcessor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptProcessor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e991-110">Ruft ab oder legt den absoluten Pfad für die FastCGI-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="1e991-110">Gets or sets the absolute path to the FastCGI application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>