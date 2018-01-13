<Type Name="DataLakeAnalyticsCatalogCredentialDeleteParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsCatalogCredentialDeleteParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsCatalogCredentialDeleteParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsCatalogCredentialDeleteParameters" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsCatalogCredentialDeleteParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7f715-101">Data Lake Analytics-Katalog löschen Anmeldeparameter.</span><span class="sxs-lookup"><span data-stu-id="7f715-101">Data Lake Analytics catalog credential deletion parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogCredentialDeleteParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7f715-102">Initialisiert eine neue Instanz der DataLakeAnalyticsCatalogCredentialDeleteParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7f715-102">Initializes a new instance of the DataLakeAnalyticsCatalogCredentialDeleteParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogCredentialDeleteParameters (string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters : string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters password" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password"><span data-ttu-id="7f715-103">das aktuelle Kennwort für die Anmeldeinformationen und den Benutzer mit Zugriff auf die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="7f715-103">the current password for the credential and user with access to the data source.</span></span> <span data-ttu-id="7f715-104">Dies ist erforderlich, wenn der Antragsteller nicht Besitzer des Kontos ist.</span><span class="sxs-lookup"><span data-stu-id="7f715-104">This is required if the requester is not the account owner.</span></span></param>
        <summary>
            <span data-ttu-id="7f715-105">Initialisiert eine neue Instanz der DataLakeAnalyticsCatalogCredentialDeleteParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7f715-105">Initializes a new instance of the DataLakeAnalyticsCatalogCredentialDeleteParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="7f715-106">Ruft ab oder legt das aktuelle Kennwort für die Anmeldeinformationen und den Benutzer mit Zugriff auf die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="7f715-106">Gets or sets the current password for the credential and user with access to the data source.</span></span> <span data-ttu-id="7f715-107">Dies ist erforderlich, wenn der Antragsteller nicht Besitzer des Kontos ist.</span><span class="sxs-lookup"><span data-stu-id="7f715-107">This is required if the requester is not the account owner.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>