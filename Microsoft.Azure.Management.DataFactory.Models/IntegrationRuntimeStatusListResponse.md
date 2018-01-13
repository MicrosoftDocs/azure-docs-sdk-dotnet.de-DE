<Type Name="IntegrationRuntimeStatusListResponse" FullName="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse">
  <TypeSignature Language="C#" Value="public class IntegrationRuntimeStatusListResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IntegrationRuntimeStatusListResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class IntegrationRuntimeStatusListResponse" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimeStatusListResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bf6ae-101">Eine Liste der Status der Verzeichnisintegration-Laufzeit.</span><span class="sxs-lookup"><span data-stu-id="bf6ae-101">A list of integration runtime status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeStatusListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf6ae-102">Initialisiert eine neue Instanz der IntegrationRuntimeStatusListResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf6ae-102">Initializes a new instance of the IntegrationRuntimeStatusListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeStatusListResponse (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; value, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; value, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As IList(Of IntegrationRuntimeStatusResponse), Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse" Usage="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse (value, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="bf6ae-103">Liste der Status der Verzeichnisintegration-Laufzeit.</span><span class="sxs-lookup"><span data-stu-id="bf6ae-103">List of integration runtime status.</span></span></param>
        <param name="nextLink"><span data-ttu-id="bf6ae-104">Der Link zur nächsten Seite der Ergebnisse, wenn keine weiteren Ergebnisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="bf6ae-104">The link to the next page of results, if any remaining results exist.</span></span></param>
        <summary>
            <span data-ttu-id="bf6ae-105">Initialisiert eine neue Instanz der IntegrationRuntimeStatusListResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf6ae-105">Initializes a new instance of the IntegrationRuntimeStatusListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf6ae-106">Ruft ab oder legt den Link zur nächsten Seite der Ergebnisse, wenn keine weiteren Ergebnisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="bf6ae-106">Gets or sets the link to the next page of results, if any remaining results exist.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="integrationRuntimeStatusListResponse.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf6ae-107">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bf6ae-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf6ae-108">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bf6ae-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of IntegrationRuntimeStatusResponse)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusListResponse.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf6ae-109">Ruft ab, oder legt ihn fest Liste des Laufzeitstatus der Integration.</span><span class="sxs-lookup"><span data-stu-id="bf6ae-109">Gets or sets list of integration runtime status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>