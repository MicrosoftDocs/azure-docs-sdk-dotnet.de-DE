<Type Name="ServicePartitionKey" FullName="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">
  <TypeSignature Language="C#" Value="public sealed class ServicePartitionKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePartitionKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePartitionKey" />
  <TypeSignature Language="F#" Value="type ServicePartitionKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Definiert einen Schlüssel zum Adressieren einer Dienstpartition.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Instanziiert eine ServicePartitionKey für partitionierte Singleton-Dienst an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionKey (long partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionKey : int64 -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Wert des partitionsschlüssels Int64-Typ</param>
        <summary>
            Instanziiert eine ServicePartitionKey für einheitliche partitioniert int64-Dienst an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionKey (string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionKey : string -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Wert des benannten partitionsschlüssels</param>
        <summary>
            Instanziiert eine ServicePartitionKey für benannte partitionierte Dienste an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ServicePartitionKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServicePartitionKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.ServicePartitionKind" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Art des partitionsschlüssels, die auf angewendet wird.
            </summary>
        <value>Partitionstyp</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Singleton">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.ServiceFabric.Services.Client.ServicePartitionKey Singleton;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey Singleton" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.Singleton" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Singleton As ServicePartitionKey " />
      <MemberSignature Language="F#" Value=" staticval mutable Singleton : Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.Singleton" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.ServicePartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt eine ServicePartitionKey, die eine Singleton-Partition angibt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Wert des partitionsschlüssels ab. Dieser Wert kann auf Grundlage des Werts der Kind-Eigenschaft der Typ umgewandelt werden.
            </summary>
        <value>Partitionsschlüssel</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>