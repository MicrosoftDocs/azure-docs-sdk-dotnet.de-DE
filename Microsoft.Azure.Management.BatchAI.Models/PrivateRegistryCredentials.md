<Type Name="PrivateRegistryCredentials" FullName="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials">
  <TypeSignature Language="C#" Value="public class PrivateRegistryCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PrivateRegistryCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class PrivateRegistryCredentials" />
  <TypeSignature Language="F#" Value="type PrivateRegistryCredentials = class" />
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
            Anmeldeinformationen für den Zugriff auf ein containerimage in einem privaten Repository.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrivateRegistryCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PrivateRegistryCredentials-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrivateRegistryCredentials (string username, string password = null, Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference passwordSecretReference = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string username, string password, class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference passwordSecretReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (username As String, Optional password As String = null, Optional passwordSecretReference As KeyVaultSecretReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials : string * string * Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference -&gt; Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials" Usage="new Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials (username, password, passwordSecretReference)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="passwordSecretReference" Type="Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference" />
      </Parameters>
      <Docs>
        <param name="username">Der Benutzername für die Anmeldung.</param>
        <param name="password">Kennwort zum Anmelden.</param>
        <param name="passwordSecretReference">Gibt den Speicherort des Kennworts, die einen Key Vault geheimen Schlüssel ist.</param>
        <summary>
            Initialisiert eine neue Instanz der PrivateRegistryCredentials-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Kennwort für die Anmeldung.
            </summary>
        <value>To be added.</value>
        <remarks>
            Das Kennwort oder PasswordSecretReference muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordSecretReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference PasswordSecretReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference PasswordSecretReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.PasswordSecretReference" />
      <MemberSignature Language="VB.NET" Value="Public Property PasswordSecretReference As KeyVaultSecretReference" />
      <MemberSignature Language="F#" Value="member this.PasswordSecretReference : Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.PasswordSecretReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passwordSecretReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt den Speicherort des Kennworts, das ein Schlüssel Vault Geheimnis ist, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Benutzer können ihre geheime Schlüssel in Azure KeyVault speichern und übergibt ihn dann an den Batch AI-Dienst für die Integration von KeyVault. Das Kennwort oder PasswordSecretReference muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie Benutzernamen, die Anmeldung fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="privateRegistryCredentials.Validate " />
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