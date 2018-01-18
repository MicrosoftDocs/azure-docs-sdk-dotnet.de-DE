<Type Name="KeyVaultKeyReference" FullName="Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference">
  <TypeSignature Language="C#" Value="public class KeyVaultKeyReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultKeyReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultKeyReference" />
  <TypeSignature Language="F#" Value="type KeyVaultKeyReference = class" />
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
            <span data-ttu-id="56f93-101">Beschreibt einen Verweis auf die Key Vault-Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="56f93-101">Describes a reference to Key Vault Key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultKeyReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="56f93-102">Initialisiert eine neue Instanz der KeyVaultKeyReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="56f93-102">Initializes a new instance of the KeyVaultKeyReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultKeyReference (Microsoft.Azure.Management.BatchAI.Models.ResourceId sourceVault, string keyUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.ResourceId sourceVault, string keyUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference.#ctor(Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceVault As ResourceId, keyUrl As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference : Microsoft.Azure.Management.BatchAI.Models.ResourceId * string -&gt; Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference" Usage="new Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference (sourceVault, keyUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="keyUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceVault"><span data-ttu-id="56f93-103">Vollqualifizierte Ressourcen-Id für den Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="56f93-103">Fully qualified resource Id for the Key Vault.</span></span></param>
        <param name="keyUrl"><span data-ttu-id="56f93-104">Die URL verweisen auf einen Schlüssel in einem Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="56f93-104">The URL referencing a key in a Key Vault.</span></span></param>
        <summary>
            <span data-ttu-id="56f93-105">Initialisiert eine neue Instanz der KeyVaultKeyReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="56f93-105">Initializes a new instance of the KeyVaultKeyReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyUrl">
      <MemberSignature Language="C#" Value="public string KeyUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference.KeyUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyUrl As String" />
      <MemberSignature Language="F#" Value="member this.KeyUrl : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference.KeyUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="56f93-106">Ruft ab oder legt die URL verweisen auf einen Schlüssel in einem Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="56f93-106">Gets or sets the URL referencing a key in a Key Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As ResourceId" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference.SourceVault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56f93-107">Ruft ab oder legt den vollqualifizierten-Ressourcen-Id für den Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="56f93-107">Gets or sets fully qualified resource Id for the Key Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.KeyVaultKeyReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultKeyReference.Validate " />
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
            <span data-ttu-id="56f93-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="56f93-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="56f93-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="56f93-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>