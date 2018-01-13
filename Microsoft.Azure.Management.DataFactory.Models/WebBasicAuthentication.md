<Type Name="WebBasicAuthentication" FullName="Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication">
  <TypeSignature Language="C#" Value="public class WebBasicAuthentication : Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebBasicAuthentication extends Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication" />
  <TypeSignature Language="VB.NET" Value="Public Class WebBasicAuthentication&#xA;Inherits WebLinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type WebBasicAuthentication = class&#xA;    inherit WebLinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Basic")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine WebLinkedService, die Standardauthentifizierung verwendet, um die Kommunikation mit einem HTTP-Endpunkt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebBasicAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der WebBasicAuthentication-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebBasicAuthentication (object url, object username, Microsoft.Azure.Management.DataFactory.Models.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object url, object username, class Microsoft.Azure.Management.DataFactory.Models.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.#ctor(System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As Object, username As Object, password As SecureString)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication : obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString -&gt; Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication" Usage="new Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication (url, username, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
      </Parameters>
      <Docs>
        <param name="url">Die URL des des Webdienst-Endpunkts, z. B. http://www.microsoft.com. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="username">Der Benutzername für die Standardauthentifizierung. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="password">Das Kennwort für die Standardauthentifizierung.</param>
        <summary>
            Initialisiert eine neue Instanz der WebBasicAuthentication-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Kennwort für die Standardauthentifizierung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Benutzername für die Standardauthentifizierung. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webBasicAuthentication.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>