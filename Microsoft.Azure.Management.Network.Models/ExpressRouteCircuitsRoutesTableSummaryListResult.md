<Type Name="ExpressRouteCircuitsRoutesTableSummaryListResult" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitsRoutesTableSummaryListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitsRoutesTableSummaryListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitsRoutesTableSummaryListResult" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitsRoutesTableSummaryListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Antwort für ListRoutesTable Verbindungen-API für Express Route zugeordnet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitsRoutesTableSummaryListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ExpressRouteCircuitsRoutesTableSummaryListResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitsRoutesTableSummaryListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary&gt; value = null, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary&gt; value, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As IList(Of ExpressRouteCircuitRoutesTableSummary) = null, Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult (value, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary&gt;" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value">Eine Liste der Routen-Tabelle.</param>
        <param name="nextLink">Die URL zum Abrufen des nächsten Satzes von Ergebnissen.</param>
        <summary>
            Initialisiert eine neue Instanz der ExpressRouteCircuitsRoutesTableSummaryListResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt die URL zum Abrufen des nächsten Satzes von Ergebnissen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of ExpressRouteCircuitRoutesTableSummary)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTableSummary&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Routen-Tabelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>