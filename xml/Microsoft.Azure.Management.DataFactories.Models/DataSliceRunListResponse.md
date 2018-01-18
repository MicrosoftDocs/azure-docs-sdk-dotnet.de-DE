<Type Name="DataSliceRunListResponse" FullName="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse">
  <TypeSignature Language="C#" Value="public class DataSliceRunListResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSliceRunListResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSliceRunListResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type DataSliceRunListResponse = class&#xA;    inherit AzureOperationResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b829f-101">Der Datenslice Liste führt Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="b829f-101">The List data slice runs operation response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSliceRunListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b829f-102">Initialisiert eine neue Instanz der DataSliceRunListResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b829f-102">Initializes a new instance of the DataSliceRunListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSliceRunListResponse (string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nextLink As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse : string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse" Usage="new Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse nextLink" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nextLink">To be added.</param>
        <summary>
            <span data-ttu-id="b829f-103">Initialisiert eine neue Instanz der DataSliceRunListResponse-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="b829f-103">Initializes a new instance of the DataSliceRunListResponse class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSliceRuns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRun&gt; DataSliceRuns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRun&gt; DataSliceRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse.DataSliceRuns" />
      <MemberSignature Language="VB.NET" Value="Public Property DataSliceRuns As IList(Of DataSliceRun)" />
      <MemberSignature Language="F#" Value="member this.DataSliceRuns : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRun&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse.DataSliceRuns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRun&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b829f-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="b829f-104">Optional.</span></span> <span data-ttu-id="b829f-105">Liste der Datenslices.</span><span class="sxs-lookup"><span data-stu-id="b829f-105">List of data slices.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b829f-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b829f-106">Required.</span></span> <span data-ttu-id="b829f-107">Der Link (Url) auf die nächste Seite der Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="b829f-107">The link (url) to the next page of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>