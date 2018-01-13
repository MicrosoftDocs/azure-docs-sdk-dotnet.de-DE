<Type Name="UserAccountSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings">
  <TypeSignature Language="C#" Value="public class UserAccountSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccountSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccountSettings" />
  <TypeSignature Language="F#" Value="type UserAccountSettings = class" />
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
            Einstellungen für das Benutzerkonto, das auf jedem auf den Knoten eines Clusters erstellt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccountSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der UserAccountSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccountSettings (string adminUserName, string adminUserSshPublicKey = null, string adminUserPassword = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string adminUserName, string adminUserSshPublicKey, string adminUserPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (adminUserName As String, Optional adminUserSshPublicKey As String = null, Optional adminUserPassword As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings : string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings (adminUserName, adminUserSshPublicKey, adminUserPassword)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="adminUserName" Type="System.String" />
        <Parameter Name="adminUserSshPublicKey" Type="System.String" />
        <Parameter Name="adminUserPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminUserName">Gibt den Namen des Administratorkontos an.</param>
        <param name="adminUserSshPublicKey">Öffentliche SSH-Schlüssel verwendet, um die Authentifizierung mit Linux basieren VMs. Dies ist nicht in einer GET-Antworttext zurückgegeben.</param>
        <param name="adminUserPassword">Der Administrator das Kennwort (nur für Linux).
            Dies ist nicht in einer GET-Antworttext zurückgegeben.</param>
        <summary>
            Initialisiert eine neue Instanz der UserAccountSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserName">
      <MemberSignature Language="C#" Value="public string AdminUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserName As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Namen des Administratorkontos an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserPassword">
      <MemberSignature Language="C#" Value="public string AdminUserPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserPassword : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Admin Benutzer das Kennwort (nur für Linux). Dies ist nicht in einer GET-Antworttext zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserSshPublicKey">
      <MemberSignature Language="C#" Value="public string AdminUserSshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserSshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserSshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserSshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserSshPublicKey : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserSshPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserSshPublicKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest öffentlichen SSH-Schlüssel zur Authentifizierung mit Linux-basierten virtuellen Computern herstellen. Dies ist nicht in einer GET-Antworttext zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userAccountSettings.Validate " />
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