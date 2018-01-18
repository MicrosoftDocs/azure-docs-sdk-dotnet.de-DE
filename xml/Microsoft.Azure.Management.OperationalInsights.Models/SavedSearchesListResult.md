<Type Name="SavedSearchesListResult" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult">
  <TypeSignature Language="C#" Value="public class SavedSearchesListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SavedSearchesListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class SavedSearchesListResult" />
  <TypeSignature Language="F#" Value="type SavedSearchesListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="027cb-101">Die Antwort für den gespeicherten Suchvorgang-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="027cb-101">The saved search operation response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SavedSearchesListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="027cb-102">Initialisiert eine neue Instanz der SavedSearchesListResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="027cb-102">Initializes a new instance of the SavedSearchesListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SavedSearchesListResult (Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata metadata = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata metadata, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult.#ctor(Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata,System.Collections.Generic.IList{Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional metadata As SearchMetadata = null, Optional value As IList(Of SavedSearch) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult : Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult (metadata, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadata" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;" />
      </Parameters>
      <Docs>
        <param name="metadata"><span data-ttu-id="027cb-103">Die Metadaten aus den Suchergebnissen.</span><span class="sxs-lookup"><span data-stu-id="027cb-103">The metadata from search results.</span></span></param>
        <param name="value"><span data-ttu-id="027cb-104">Das Array von Ergebniswerte.</span><span class="sxs-lookup"><span data-stu-id="027cb-104">The array of result values.</span></span></param>
        <summary>
            <span data-ttu-id="027cb-105">Initialisiert eine neue Instanz der SavedSearchesListResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="027cb-105">Initializes a new instance of the SavedSearchesListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As SearchMetadata" />
      <MemberSignature Language="F#" Value="member this.Metadata : Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="__metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="027cb-106">Ruft ab oder legt die Metadaten aus den Suchergebnissen.</span><span class="sxs-lookup"><span data-stu-id="027cb-106">Gets or sets the metadata from search results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of SavedSearch)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="027cb-107">Ruft ab oder legt das Array von Ergebniswerte.</span><span class="sxs-lookup"><span data-stu-id="027cb-107">Gets or sets the array of result values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>