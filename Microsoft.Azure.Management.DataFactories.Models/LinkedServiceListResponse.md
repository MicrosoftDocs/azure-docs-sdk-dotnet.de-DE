<Type Name="LinkedServiceListResponse" FullName="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse">
  <TypeSignature Language="C#" Value="public class LinkedServiceListResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinkedServiceListResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class LinkedServiceListResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type LinkedServiceListResponse = class&#xA;    inherit AzureOperationResponse" />
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
            <span data-ttu-id="ec4e2-101">Liste Data Factory LinkedServices Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ec4e2-101">The List data factory linkedServices operation response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkedServiceListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec4e2-102">Initialisiert eine neue Instanz der LinkedServiceListResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ec4e2-102">Initializes a new instance of the LinkedServiceListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkedServiceListResponse (string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nextLink As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse : string -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse" Usage="new Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse nextLink" />
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
            <span data-ttu-id="ec4e2-103">Initialisiert eine neue Instanz der LinkedServiceListResponse-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="ec4e2-103">Initializes a new instance of the LinkedServiceListResponse class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt; LinkedServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt; LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServices As IList(Of LinkedService)" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse.LinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec4e2-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="ec4e2-104">Optional.</span></span> <span data-ttu-id="ec4e2-105">Alle Data Factory LinkedService Instanzen.</span><span class="sxs-lookup"><span data-stu-id="ec4e2-105">All the data factory linkedService instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse.NextLink" />
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
            <span data-ttu-id="ec4e2-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ec4e2-106">Required.</span></span> <span data-ttu-id="ec4e2-107">Der Link (Url) auf die nächste Seite der Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="ec4e2-107">The link (url) to the next page of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>