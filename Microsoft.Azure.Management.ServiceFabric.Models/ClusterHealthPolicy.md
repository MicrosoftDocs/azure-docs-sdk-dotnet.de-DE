<Type Name="ClusterHealthPolicy" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterHealthPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Definiert eine Integritätsrichtlinie, die zur Bewertung der Integritäts des Clusters oder eines Clusterknotens.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ClusterHealthPolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthPolicy (Nullable&lt;int&gt; maxPercentUnhealthyNodes = null, Nullable&lt;int&gt; maxPercentUnhealthyApplications = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; maxPercentUnhealthyNodes, valuetype System.Nullable`1&lt;int32&gt; maxPercentUnhealthyApplications) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxPercentUnhealthyNodes As Nullable(Of Integer) = null, Optional maxPercentUnhealthyApplications As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy : Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy (maxPercentUnhealthyNodes, maxPercentUnhealthyApplications)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxPercentUnhealthyNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxPercentUnhealthyApplications" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxPercentUnhealthyNodes">Der maximal zulässige Prozentsatz fehlerhafter Knoten, bevor ein Fehler gemeldet wird. Z. B. 10 % der Knoten fehlerhaft sein dürfen, wäre dieser Wert
            10. </param>
        <param name="maxPercentUnhealthyApplications">Der maximal zulässige Prozentsatz fehlerhafter Anwendungen, bevor ein Fehler gemeldet wird. Soll es z. B.zulässig sein, dass 10 % der Anwendungen fehlerhaft sind, muss dieser Wert gleich „10“ sein. </param>
        <summary>
            Initialisiert eine neue Instanz der ClusterHealthPolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxPercentUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyApplications As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentUnhealthyApplications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximal zulässige Prozentsatz fehlerhafter Anwendungen, bevor ein Fehler gemeldet. Soll es z. B.zulässig sein, dass 10 % der Anwendungen fehlerhaft sind, muss dieser Wert gleich „10“ sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxPercentUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentUnhealthyNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximal zulässige Prozentsatz fehlerhafter Knoten, bevor ein Fehler gemeldet. Soll es z. B.zulässig sein, dass 10 % der Knoten fehlerhaft sind, muss dieser Wert gleich „10“ sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clusterHealthPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>