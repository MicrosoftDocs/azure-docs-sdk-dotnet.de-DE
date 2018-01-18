<Type Name="UpdateStorageAccountParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters">
  <TypeSignature Language="C#" Value="public class UpdateStorageAccountParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateStorageAccountParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateStorageAccountParameters" />
  <TypeSignature Language="F#" Value="type UpdateStorageAccountParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c1281-101">Speicher-Konto-Parametern für ein Speicherkonto in ein Data Lake Analytics-Konto aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="c1281-101">Storage account parameters for a storage account being updated in a Data Lake Analytics account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateStorageAccountParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c1281-102">Initialisiert eine neue Instanz der UpdateStorageAccountParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c1281-102">Initializes a new instance of the UpdateStorageAccountParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateStorageAccountParameters (string accessKey = null, string suffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accessKey, string suffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accessKey As String = null, Optional suffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters : string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters (accessKey, suffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accessKey" Type="System.String" />
        <Parameter Name="suffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accessKey"><span data-ttu-id="c1281-103">der aktualisierte Zugriffsschlüssel zugeordneten dieser Azure Storage-Konto, das zum Herstellen der Verbindung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="c1281-103">the updated access key associated with this Azure Storage account that will be used to connect to it.</span></span></param>
        <param name="suffix"><span data-ttu-id="c1281-104">Das optionale Suffix für das Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="c1281-104">the optional suffix for the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="c1281-105">Initialisiert eine neue Instanz der UpdateStorageAccountParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c1281-105">Initializes a new instance of the UpdateStorageAccountParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKey">
      <MemberSignature Language="C#" Value="public string AccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters.AccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKey As String" />
      <MemberSignature Language="F#" Value="member this.AccessKey : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters.AccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1281-106">Ruft ab oder legt den aktualisierten zugeordneten Zugriffsschlüssel für dieses Azure-Speicher-Konto, das zum Herstellen der Verbindung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="c1281-106">Gets or sets the updated access key associated with this Azure Storage account that will be used to connect to it.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suffix">
      <MemberSignature Language="C#" Value="public string Suffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Suffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters.Suffix" />
      <MemberSignature Language="VB.NET" Value="Public Property Suffix As String" />
      <MemberSignature Language="F#" Value="member this.Suffix : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters.Suffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1281-107">Ermittelt oder definiert den optionalen Suffixe für das Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="c1281-107">Gets or sets the optional suffix for the storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>