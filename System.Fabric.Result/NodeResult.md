<Type Name="NodeResult" FullName="System.Fabric.Result.NodeResult">
  <TypeSignature Language="C#" Value="public class NodeResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit NodeResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.NodeResult" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeResult" />
  <TypeSignature Language="F#" Value="type NodeResult = class" />
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
            Gibt Knoten-Ergebnisobjekt. 
            </summary>
    <remarks>
            Diese Klasse gibt die "nodename" und NodeInstanceId zurück. Diese Klasse ist Teil von RestartNode StartNode, stopnode-Aufruf steht Aktionen Struktur ergeben.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeInstance">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstance" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.NodeResult.NodeInstance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstance As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstance : System.Numerics.BigInteger" Usage="System.Fabric.Result.NodeResult.NodeInstance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Instanz-Id von Knoten ab.
            </summary>
        <value>Die Instanz-Id von Knoten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.NodeResult.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Result.NodeResult.NodeName" />
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
            Ruft Name des Knotens ab.
            </summary>
        <value>Der Knotenname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.NodeResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeResult.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolge wie zurück: "" nodename ":" string "," NodeInstance: BigInteger "
            </summary>
        <returns>Eine Zeichenfolge</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>