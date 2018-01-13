<Type Name="HttpLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig">
  <TypeSignature Language="C#" Value="public class HttpLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpLogsConfig" />
  <TypeSignature Language="F#" Value="type HttpLogsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Konfiguration des HTTP-Protokolle.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der HttpLogsConfig-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpLogsConfig (Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig fileSystem = null, Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig azureBlobStorage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig fileSystem, class Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig azureBlobStorage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig.#ctor(Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig,Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional fileSystem As FileSystemHttpLogsConfig = null, Optional azureBlobStorage As AzureBlobStorageHttpLogsConfig = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig : Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig * Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig (fileSystem, azureBlobStorage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fileSystem" Type="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig" />
        <Parameter Name="azureBlobStorage" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig" />
      </Parameters>
      <Docs>
        <param name="fileSystem">HTTP-Protokolle auf die Konfiguration des Dateisystems.</param>
        <param name="azureBlobStorage">HTTP-Protokolle auf Azure-Blob-Speicherkonfiguration.</param>
        <summary>
            Initialisiert eine neue Instanz der HttpLogsConfig-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBlobStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig AzureBlobStorage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig AzureBlobStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig.AzureBlobStorage" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureBlobStorage As AzureBlobStorageHttpLogsConfig" />
      <MemberSignature Language="F#" Value="member this.AzureBlobStorage : Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig.AzureBlobStorage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureBlobStorage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageHttpLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt HTTP-Protokolle zu Azure-Blob-Speicherkonfiguration.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileSystem">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig FileSystem { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig FileSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig.FileSystem" />
      <MemberSignature Language="VB.NET" Value="Public Property FileSystem As FileSystemHttpLogsConfig" />
      <MemberSignature Language="F#" Value="member this.FileSystem : Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig.FileSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileSystem")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt HTTP-Protokolle zu Datei-Systemkonfiguration.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HttpLogsConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="httpLogsConfig.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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