<Type Name="AzureBlobFileSystemReference" FullName="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference">
  <TypeSignature Language="C#" Value="public class AzureBlobFileSystemReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobFileSystemReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobFileSystemReference" />
  <TypeSignature Language="F#" Value="type AzureBlobFileSystemReference = class" />
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
            Stellt die erforderlichen Informationen, die für den Dienst zu Azure-blobspeichercontainer auf den Clusterknoten bereitstellen können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobFileSystemReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureBlobFileSystemReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobFileSystemReference (string accountName, string containerName, Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo credentials, string relativeMountPath, string mountOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string containerName, class Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo credentials, string relativeMountPath, string mountOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, containerName As String, credentials As AzureStorageCredentialsInfo, relativeMountPath As String, Optional mountOptions As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference : string * string * Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference" Usage="new Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference (accountName, containerName, credentials, relativeMountPath, mountOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo" />
        <Parameter Name="relativeMountPath" Type="System.String" />
        <Parameter Name="mountOptions" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">Name des Azure Blob Storage-Kontos.</param>
        <param name="containerName">Der Name des Containers Azure Blob-Speicher im Cluster bereitgestellt.</param>
        <param name="credentials">Informationen der Anmeldeinformationen für das Azure Blob Storage-Konto.</param>
        <param name="relativeMountPath">Gibt den relativen Pfad auf den Computeknoten, von dem die Azure-Blob im Dateisystem bereitgestellt werden.</param>
        <param name="mountOptions">Gibt die verschiedenen Mount-Optionen, die zum Konfigurieren von Blob-Dateisystem verwendet werden können.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureBlobFileSystemReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Azure Blob Storage-Kontos fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.ContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Name des Containers Azure Blob-Speicher im Cluster bereitgestellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As AzureStorageCredentialsInfo" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.Credentials" />
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
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest von Anmeldeinformationen für das Azure Blob Storage-Konto.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountOptions">
      <MemberSignature Language="C#" Value="public string MountOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MountOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.MountOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property MountOptions As String" />
      <MemberSignature Language="F#" Value="member this.MountOptions : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.MountOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die verschiedenen Mount-Optionen, die zum Konfigurieren von Blob-Dateisystem verwendet werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeMountPath">
      <MemberSignature Language="C#" Value="public string RelativeMountPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativeMountPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.RelativeMountPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeMountPath As String" />
      <MemberSignature Language="F#" Value="member this.RelativeMountPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.RelativeMountPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativeMountPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den relativen Pfad auf den Computeknoten, von dem die Azure-Blob im Dateisystem bereitgestellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Beachten Sie, dass alle Blob-Dateisystemen unter "Location" $AZ_BATCHAI_MOUNT_ROOT bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureBlobFileSystemReference.Validate " />
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