<Type Name="TrafficManagerGeographicHierarchy" FullName="Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy">
  <TypeSignature Language="C#" Value="public class TrafficManagerGeographicHierarchy : Microsoft.Azure.Management.TrafficManager.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TrafficManagerGeographicHierarchy extends Microsoft.Azure.Management.TrafficManager.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy" />
  <TypeSignature Language="VB.NET" Value="Public Class TrafficManagerGeographicHierarchy&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type TrafficManagerGeographicHierarchy = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.TrafficManager.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Klasse, die die geografische Hierarchie verwendet wird, mit der geografischen verkehrsroutingmethode darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrafficManagerGeographicHierarchy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TrafficManagerGeographicHierarchy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrafficManagerGeographicHierarchy (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.TrafficManager.Models.Region geographicHierarchy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.TrafficManager.Models.Region geographicHierarchy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.TrafficManager.Models.Region)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional geographicHierarchy As Region = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.TrafficManager.Models.Region -&gt; Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy" Usage="new Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy (id, name, type, location, tags, geographicHierarchy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="geographicHierarchy" Type="Microsoft.Azure.Management.TrafficManager.Models.Region" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="location">Speicherort von Ressourcen</param>
        <param name="tags">Ressourcentags</param>
        <param name="geographicHierarchy">Der Bereich am Stamm der Hierarchie aus allen Regionen in der Hierarchie kann abgerufen werden.</param>
        <summary>
            Initialisiert eine neue Instanz der TrafficManagerGeographicHierarchy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeographicHierarchy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Models.Region GeographicHierarchy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Models.Region GeographicHierarchy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy.GeographicHierarchy" />
      <MemberSignature Language="VB.NET" Value="Public Property GeographicHierarchy As Region" />
      <MemberSignature Language="F#" Value="member this.GeographicHierarchy : Microsoft.Azure.Management.TrafficManager.Models.Region with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy.GeographicHierarchy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geographicHierarchy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.Region</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt es fest die Region am Stamm der Hierarchie alles, was die Regionen, in der Hierarchie abgerufen werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>