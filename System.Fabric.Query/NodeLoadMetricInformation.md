<Type Name="NodeLoadMetricInformation" FullName="System.Fabric.Query.NodeLoadMetricInformation">
  <TypeSignature Language="C#" Value="public sealed class NodeLoadMetricInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeLoadMetricInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.NodeLoadMetricInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeLoadMetricInformation" />
  <TypeSignature Language="F#" Value="type NodeLoadMetricInformation = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die Datenstruktur, die Informationen für eine bestimmte Metrik geladen werden, auf einen Knoten enthält.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeLoadMetricInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.NodeLoadMetricInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.NodeLoadMetricInformation" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferedNodeCapacityRemaining">
      <MemberSignature Language="C#" Value="public double BufferedNodeCapacityRemaining { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 BufferedNodeCapacityRemaining" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.BufferedNodeCapacityRemaining" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BufferedNodeCapacityRemaining As Double" />
      <MemberSignature Language="F#" Value="member this.BufferedNodeCapacityRemaining : double" Usage="System.Fabric.Query.NodeLoadMetricInformation.BufferedNodeCapacityRemaining" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft einen Wert, der die verbleibende Kapazität gibt an, um die nicht von NodeBufferPercentage reserviert ist.</para>
        </summary>
        <value>
          <para>Die verbleibende Kapazität nicht für die Metrik für den Knoten NodeBufferPercentage reserviert ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentNodeLoad">
      <MemberSignature Language="C#" Value="public double CurrentNodeLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 CurrentNodeLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.CurrentNodeLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentNodeLoad As Double" />
      <MemberSignature Language="F#" Value="member this.CurrentNodeLoad : double" Usage="System.Fabric.Query.NodeLoadMetricInformation.CurrentNodeLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>&gt;Ruft die aktuelle Last auf dem Knoten für eine Metrik.</para>
        </summary>
        <value>
          <para>Die aktuelle Auslastung auf den Knoten für eine Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCapacityViolation">
      <MemberSignature Language="C#" Value="public bool IsCapacityViolation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsCapacityViolation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.IsCapacityViolation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsCapacityViolation As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsCapacityViolation : bool" Usage="System.Fabric.Query.NodeLoadMetricInformation.IsCapacityViolation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft einen Wert, der angibt, ob eine kapazitätsverletzung für die Metrik für den angegebenen Knoten vorhanden ist.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> liegt eine kapazitätsverletzung für die Metrik für den angegebenen Knoten ist; andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.NodeLoadMetricInformation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen der Metrik.</para>
        </summary>
        <value>
          <para>Der Name der Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeBufferedCapacity">
      <MemberSignature Language="C#" Value="public long NodeBufferedCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeBufferedCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeBufferedCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeBufferedCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeBufferedCapacity : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeBufferedCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft einen Wert, der die Kapazität gibt an, um die nicht von NodeBufferPercentage reserviert ist.</para>
        </summary>
        <value>
          <para>Die Kapazität, die nicht für die Metrik für den Knoten von NodeBufferPercentage reserviert ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCapacity">
      <MemberSignature Language="C#" Value="public long NodeCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeCapacity : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die gesamte Kapazität auf dem Knoten für die Metrik ab.</para>
        </summary>
        <value>
          <para>Die Gesamtkapazität auf den Knoten für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCapacityRemaining">
      <MemberSignature Language="C#" Value="public double NodeCapacityRemaining { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NodeCapacityRemaining" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeCapacityRemaining" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeCapacityRemaining As Double" />
      <MemberSignature Language="F#" Value="member this.NodeCapacityRemaining : double" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeCapacityRemaining" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die verbleibende Kapazität auf dem Knoten für die Metrik ab.</para>
        </summary>
        <value>
          <para>Die verbleibende Kapazität auf dem Knoten für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeLoad">
      <MemberSignature Language="C#" Value="public long NodeLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeLoad As Long" />
      <MemberSignature Language="F#" Value="member this.NodeLoad : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die aktuelle Last auf dem Knoten für eine Metrik.</para>
          <para>
            In zukünftigen Versionen von Service Fabric dieser Parameter als veraltet zugunsten des markiert wird <see cref="P:System.Fabric.Query.NodeLoadMetricInformation.CurrentNodeLoad" />.
            </para>
        </summary>
        <value>
          <para>Die aktuelle Auslastung auf den Knoten für eine Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeRemainingBufferedCapacity">
      <MemberSignature Language="C#" Value="public long NodeRemainingBufferedCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeRemainingBufferedCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeRemainingBufferedCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeRemainingBufferedCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeRemainingBufferedCapacity : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeRemainingBufferedCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft einen Wert, der die verbleibende Kapazität gibt an, um die nicht von NodeBufferPercentage reserviert ist.</para>
          <para>
            In zukünftigen Versionen von Service Fabric dieser Parameter als veraltet zugunsten des markiert wird <see cref="P:System.Fabric.Query.NodeLoadMetricInformation.BufferedNodeCapacityRemaining" />.
            </para>
        </summary>
        <value>
          <para>Die verbleibende Kapazität nicht für die Metrik für den Knoten NodeBufferPercentage reserviert ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeRemainingCapacity">
      <MemberSignature Language="C#" Value="public long NodeRemainingCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeRemainingCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeRemainingCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeRemainingCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeRemainingCapacity : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeRemainingCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die verbleibende Kapazität auf dem Knoten für die Metrik ab.</para>
          <para>
            In zukünftigen Versionen von Service Fabric dieser Parameter als veraltet zugunsten des markiert wird <see cref="P:System.Fabric.Query.NodeLoadMetricInformation.NodeCapacityRemaining" />.
            </para>
        </summary>
        <value>
          <para>Die verbleibende Kapazität auf dem Knoten für die Metrik.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>