<Type Name="IntegrationRuntimeMonitoringData" FullName="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData">
  <TypeSignature Language="C#" Value="public class IntegrationRuntimeMonitoringData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IntegrationRuntimeMonitoringData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData" />
  <TypeSignature Language="VB.NET" Value="Public Class IntegrationRuntimeMonitoringData" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimeMonitoringData = class" />
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
            <span data-ttu-id="3aa49-101">Datenantwort zur netzwerküberwachung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3aa49-101">Get monitoring data response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeMonitoringData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData.#ctor" />
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
            <span data-ttu-id="3aa49-102">Initialisiert eine neue Instanz der IntegrationRuntimeMonitoringData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3aa49-102">Initializes a new instance of the IntegrationRuntimeMonitoringData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeMonitoringData (string name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData&gt; nodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData&gt; nodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional nodes As IList(Of IntegrationRuntimeNodeMonitoringData) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData" Usage="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData (name, nodes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="nodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3aa49-103">Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="3aa49-103">Integration runtime name.</span></span></param>
        <param name="nodes"><span data-ttu-id="3aa49-104">Integration Runtime Knoten Überwachungsdaten.</span><span class="sxs-lookup"><span data-stu-id="3aa49-104">Integration runtime node monitoring data.</span></span></param>
        <summary>
            <span data-ttu-id="3aa49-105">Initialisiert eine neue Instanz der IntegrationRuntimeMonitoringData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3aa49-105">Initializes a new instance of the IntegrationRuntimeMonitoringData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3aa49-106">Ruft ab, oder legt ihn fest Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="3aa49-106">Gets or sets integration runtime name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Nodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData&gt; Nodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData&gt; Nodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData.Nodes" />
      <MemberSignature Language="VB.NET" Value="Public Property Nodes As IList(Of IntegrationRuntimeNodeMonitoringData)" />
      <MemberSignature Language="F#" Value="member this.Nodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData.Nodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3aa49-107">Ruft ab, oder legt ihn fest Integration Runtime Knoten Überwachungsdaten.</span><span class="sxs-lookup"><span data-stu-id="3aa49-107">Gets or sets integration runtime node monitoring data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>