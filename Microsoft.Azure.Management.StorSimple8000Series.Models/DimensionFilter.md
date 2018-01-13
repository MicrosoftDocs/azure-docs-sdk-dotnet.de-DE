<Type Name="DimensionFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter">
  <TypeSignature Language="C#" Value="public class DimensionFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DimensionFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class DimensionFilter" />
  <TypeSignature Language="F#" Value="type DimensionFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Dimensionsfilter für die.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DimensionFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse DimensionFilter an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DimensionFilter (string name = null, string values = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional values As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter : string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter (name, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="values" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Gibt den Namen der Dimension an. Z. B. Clusternetzwerkschnittstellen. Gültige Werte sind diejenigen, die im Aufruf der ListMetricDefinitions in das Feld "Dimensionen" angegeben. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</param>
        <param name="values">Gibt den Dimensionswert. Z. B. Data0.
            Gültige Werte sind diejenigen, die in das Feld "Dimensionen" im Aufruf ListMetricDefinitions zurückgegeben. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse DimensionFilter an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt gibt den Namen der Dimension an. Z. B. Clusternetzwerkschnittstellen.
            Gültige Werte sind diejenigen, die im Aufruf der ListMetricDefinitions in das Feld "Dimensionen" angegeben. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public string Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As String" />
      <MemberSignature Language="F#" Value="member this.Values : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Dimensionswert an. Z. B. Data0. Gültige Werte sind diejenigen, die in das Feld "Dimensionen" im Aufruf ListMetricDefinitions zurückgegeben. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>