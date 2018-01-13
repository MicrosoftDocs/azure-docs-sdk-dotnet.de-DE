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
            Beschreibt einen Verweis auf die Key Vault-Schlüssels.
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
            Initialisiert eine neue Instanz der KeyVaultKeyReference-Klasse.
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
        <param name="sourceVault">Vollqualifizierte Ressourcen-Id für den Schlüsseltresor.</param>
        <param name="keyUrl">Die URL verweisen auf einen Schlüssel in einem Schlüsseltresor.</param>
        <summary>
            Initialisiert eine neue Instanz der KeyVaultKeyReference-Klasse.
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
            Ruft ab oder legt die URL verweisen auf einen Schlüssel in einem Schlüsseltresor.
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
            Ruft ab oder legt den vollqualifizierten-Ressourcen-Id für den Schlüsseltresor.
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