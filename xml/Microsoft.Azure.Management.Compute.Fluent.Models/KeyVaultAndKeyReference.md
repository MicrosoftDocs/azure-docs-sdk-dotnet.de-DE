<Type Name="KeyVaultAndKeyReference" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference">
  <TypeSignature Language="C#" Value="public class KeyVaultAndKeyReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultAndKeyReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultAndKeyReference" />
  <TypeSignature Language="F#" Value="type KeyVaultAndKeyReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="343d9-101">Key Vault-Schlüssel-Url und Tresor-Id der Schlüsselaustauschschlüssel, KeK ist optional und wird verwendet, um die "EncryptionKey" unwrap bereitgestellt</span><span class="sxs-lookup"><span data-stu-id="343d9-101">Key Vault Key Url and vault id of KeK, KeK is optional and when provided is used to unwrap the encryptionKey</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultAndKeyReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="343d9-102">Initialisiert eine neue Instanz der KeyVaultAndKeyReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="343d9-102">Initializes a new instance of the KeyVaultAndKeyReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultAndKeyReference (Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault sourceVault, string keyUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault sourceVault, string keyUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference : Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference (sourceVault, keyUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault" />
        <Parameter Name="keyUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceVault"><span data-ttu-id="343d9-103">Ressourcen-Id der KeyVault mit dem Schlüssel oder den geheimen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="343d9-103">Resource id of the KeyVault containing the key or secret</span></span></param>
        <param name="keyUrl"><span data-ttu-id="343d9-104">URL verweist auf einen Schlüssel oder den geheimen Schlüssel im KeyVault</span><span class="sxs-lookup"><span data-stu-id="343d9-104">Url pointing to a key or secret in KeyVault</span></span></param>
        <summary>
            <span data-ttu-id="343d9-105">Initialisiert eine neue Instanz der KeyVaultAndKeyReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="343d9-105">Initializes a new instance of the KeyVaultAndKeyReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyUrl">
      <MemberSignature Language="C#" Value="public string KeyUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference.KeyUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyUrl As String" />
      <MemberSignature Language="F#" Value="member this.KeyUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference.KeyUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="343d9-106">Ruft ab oder legt die Url verweist auf einen Schlüssel oder den geheimen Schlüssel im KeyVault</span><span class="sxs-lookup"><span data-stu-id="343d9-106">Gets or sets url pointing to a key or secret in KeyVault</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As SourceVault" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference.SourceVault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="343d9-107">Ruft ab oder legt ihn fest Ressourcen-Id der KeyVault mit dem Schlüssel oder den geheimen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="343d9-107">Gets or sets resource id of the KeyVault containing the key or secret</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultAndKeyReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="343d9-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="343d9-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="343d9-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="343d9-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>