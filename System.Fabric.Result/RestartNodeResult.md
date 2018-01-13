<Type Name="RestartNodeResult" FullName="System.Fabric.Result.RestartNodeResult">
  <TypeSignature Language="C#" Value="public class RestartNodeResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestartNodeResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.RestartNodeResult" />
  <TypeSignature Language="VB.NET" Value="Public Class RestartNodeResult" />
  <TypeSignature Language="F#" Value="type RestartNodeResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Gibt Neustart Knoten-Ergebnisobjekt.
            </summary>
    <remarks>
            Diese Klasse gibt die SelectedReplica und NodeResult für RestartNode-Aktion zurück.  
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeResult">
      <MemberSignature Language="C#" Value="public System.Fabric.Result.NodeResult NodeResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Result.NodeResult NodeResult" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartNodeResult.NodeResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeResult As NodeResult" />
      <MemberSignature Language="F#" Value="member this.NodeResult : System.Fabric.Result.NodeResult" Usage="System.Fabric.Result.RestartNodeResult.NodeResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Result.NodeResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die NodeResult ab.
            </summary>
        <value>Das NodeResult-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedReplica SelectedReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedReplica SelectedReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartNodeResult.SelectedReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedReplica As SelectedReplica" />
      <MemberSignature Language="F#" Value="member this.SelectedReplica : System.Fabric.SelectedReplica" Usage="System.Fabric.Result.RestartNodeResult.SelectedReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die SelectedReplica ab.
            SelectedReplica werden keine für den Fall, dass die Prüfbarkeit RestartNode-Aktion mithilfe der Knotenname ausgeführt wurde.
            </summary>
        <value>Das SelectedReplica-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.RestartNodeResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="restartNodeResult.ToString " />
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
            Formate NodeResult und SelectedReplica in eine Zeichenfolge.
            </summary>
        <returns>Die formatierte Zeichenfolge.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>