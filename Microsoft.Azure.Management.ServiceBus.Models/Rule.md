<Type Name="Rule" FullName="Microsoft.Azure.Management.ServiceBus.Models.Rule">
  <TypeSignature Language="C#" Value="public class Rule : Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Rule extends Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.Rule" />
  <TypeSignature Language="VB.NET" Value="Public Class Rule&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Rule = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibung der Regel Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Rule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Rule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Regelklasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Rule (string id = null, string name = null, string type = null, Microsoft.Azure.Management.ServiceBus.Models.Action action = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.FilterType&gt; filterType = null, Microsoft.Azure.Management.ServiceBus.Models.SqlFilter sqlFilter = null, Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter correlationFilter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.ServiceBus.Models.Action action, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.FilterType&gt; filterType, class Microsoft.Azure.Management.ServiceBus.Models.SqlFilter sqlFilter, class Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter correlationFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Rule.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.Action,System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.FilterType},Microsoft.Azure.Management.ServiceBus.Models.SqlFilter,Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.Rule : string * string * string * Microsoft.Azure.Management.ServiceBus.Models.Action * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.FilterType&gt; * Microsoft.Azure.Management.ServiceBus.Models.SqlFilter * Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter -&gt; Microsoft.Azure.Management.ServiceBus.Models.Rule" Usage="new Microsoft.Azure.Management.ServiceBus.Models.Rule (id, name, type, action, filterType, sqlFilter, correlationFilter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.ServiceBus.Models.Action" />
        <Parameter Name="filterType" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.FilterType&gt;" />
        <Parameter Name="sqlFilter" Type="Microsoft.Azure.Management.ServiceBus.Models.SqlFilter" />
        <Parameter Name="correlationFilter" Type="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="action">Stellt Filteraktionen, die zulässig sind, für die Transformation einer Nachricht, die von einem Filterausdruck abgeglichen wurden.</param>
        <param name="filterType">Filtertyp, der für ein "brokeredmessage" ausgewertet wird. Folgende Werte sind möglich: "SqlFilter", "CorrelationFilter"</param>
        <param name="sqlFilter">Eigenschaften des sqlFilter</param>
        <param name="correlationFilter">Eigenschaften des correlationFilter</param>
        <summary>
            Initialisiert eine neue Instanz der Regelklasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.Action Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.Action Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Rule.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As Action" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.Management.ServiceBus.Models.Action with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Rule.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.Action</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt stellt Filteraktionen, die zulässig sind, für die Transformation einer Nachricht, die von einem Filterausdruck abgeglichen wurden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter CorrelationFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter CorrelationFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Rule.CorrelationFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationFilter As CorrelationFilter" />
      <MemberSignature Language="F#" Value="member this.CorrelationFilter : Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Rule.CorrelationFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.correlationFilter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaften des correlationFilter
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.FilterType&gt; FilterType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.FilterType&gt; FilterType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Rule.FilterType" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterType As Nullable(Of FilterType)" />
      <MemberSignature Language="F#" Value="member this.FilterType : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.FilterType&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Rule.FilterType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filterType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.FilterType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Filtertyp, die für ein "brokeredmessage" ausgewertet wird. Folgende Werte sind möglich: "SqlFilter", "CorrelationFilter"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.SqlFilter SqlFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.SqlFilter SqlFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Rule.SqlFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlFilter As SqlFilter" />
      <MemberSignature Language="F#" Value="member this.SqlFilter : Microsoft.Azure.Management.ServiceBus.Models.SqlFilter with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Rule.SqlFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sqlFilter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SqlFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaften des sqlFilter
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>