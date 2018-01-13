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
            Die IIS-Handlerzuordnungen verwendet, um zu definieren, welche Handler HTTP-Anforderungen mit bestimmten Erweiterung verarbeitet.
            Es wird z. B. verwendet, so konfigurieren Sie Php-cgi.exe-Prozess, um alle HTTP-Anforderungen mit der Erweiterung *.PHP zu verarbeiten.
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
            Initialisiert eine neue Instanz der HandlerMapping-Klasse.
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
        <param name="extension">Anforderungen mit dieser Erweiterung werden über die angegebene FastCGI-Anwendung behandelt werden.</param>
        <param name="scriptProcessor">Der absolute Pfad der FastCGI-Anwendung.</param>
        <param name="arguments">Befehlszeilenargumente, die an den Skriptprozessor übergeben werden.</param>
        <summary>
            Initialisiert eine neue Instanz der HandlerMapping-Klasse.
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
            Ruft ab, oder legt ihn fest Befehlszeilenargumente Skriptprozessor übergeben werden soll.
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
            Ruft ab oder legt ihn fest Anforderungen mit dieser Erweiterung behandelt, die die angegebene FastCGI-Anwendung verwenden.
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
            Ruft ab oder legt den absoluten Pfad für die FastCGI-Anwendung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>