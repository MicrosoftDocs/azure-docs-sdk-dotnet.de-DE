<Type Name="ImageSourceRegistry" FullName="Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry">
  <TypeSignature Language="C#" Value="public class ImageSourceRegistry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageSourceRegistry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageSourceRegistry" />
  <TypeSignature Language="F#" Value="type ImageSourceRegistry = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Details des containerimages wie Name, URL und Anmeldeinformationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageSourceRegistry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ImageSourceRegistry-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageSourceRegistry (string image, string serverUrl = null, Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials credentials = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string image, string serverUrl, class Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (image As String, Optional serverUrl As String = null, Optional credentials As PrivateRegistryCredentials = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry : string * string * Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials -&gt; Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry" Usage="new Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry (image, serverUrl, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="image" Type="System.String" />
        <Parameter Name="serverUrl" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials" />
      </Parameters>
      <Docs>
        <param name="image">Der Name des Bilds in der Image-Repository.</param>
        <param name="serverUrl">URL für Image-Repository.</param>
        <param name="credentials">Informationen zum Zugriff auf die privaten Docker-Repositorys.</param>
        <summary>
            Initialisiert eine neue Instanz der ImageSourceRegistry-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As PrivateRegistryCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Zugriff auf die privaten Docker-Repository.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public string Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As String" />
      <MemberSignature Language="F#" Value="member this.Image : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Bilds in Image-Repository.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerUrl">
      <MemberSignature Language="C#" Value="public string ServerUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.ServerUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerUrl As String" />
      <MemberSignature Language="F#" Value="member this.ServerUrl : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.ServerUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serverUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL für Image-Repository fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageSourceRegistry.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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