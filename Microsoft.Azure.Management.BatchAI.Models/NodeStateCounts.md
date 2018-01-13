<Type Name="NodeStateCounts" FullName="Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts">
  <TypeSignature Language="C#" Value="public class NodeStateCounts" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeStateCounts extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeStateCounts" />
  <TypeSignature Language="F#" Value="type NodeStateCounts = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Anzahl der verschiedenen Status der Compute-Knoten im Cluster.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeStateCounts ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der NodeStateCounts-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeStateCounts (int idleNodeCount, int runningNodeCount, int preparingNodeCount, int unusableNodeCount, int leavingNodeCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 idleNodeCount, int32 runningNodeCount, int32 preparingNodeCount, int32 unusableNodeCount, int32 leavingNodeCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.#ctor(System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (idleNodeCount As Integer, runningNodeCount As Integer, preparingNodeCount As Integer, unusableNodeCount As Integer, leavingNodeCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts : int * int * int * int * int -&gt; Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts" Usage="new Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts (idleNodeCount, runningNodeCount, preparingNodeCount, unusableNodeCount, leavingNodeCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="idleNodeCount" Type="System.Int32" />
        <Parameter Name="runningNodeCount" Type="System.Int32" />
        <Parameter Name="preparingNodeCount" Type="System.Int32" />
        <Parameter Name="unusableNodeCount" Type="System.Int32" />
        <Parameter Name="leavingNodeCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="idleNodeCount">Anzahl der Serverknoten im Leerlauf.</param>
        <param name="runningNodeCount">Anzahl der Serverknoten die Aufträge ausgeführt werden.</param>
        <param name="preparingNodeCount">Anzahl der Computeknoten, die vorbereitet wird.</param>
        <param name="unusableNodeCount">Anzahl der Serverknoten die unbrauchbar sind.</param>
        <param name="leavingNodeCount">Anzahl der Computeknoten, die den Cluster verlassen.</param>
        <summary>
            Initialisiert eine neue Instanz der NodeStateCounts-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleNodeCount">
      <MemberSignature Language="C#" Value="public int IdleNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 IdleNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.IdleNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.IdleNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.IdleNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="idleNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl von Serverknoten im Leerlauf.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeavingNodeCount">
      <MemberSignature Language="C#" Value="public int LeavingNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LeavingNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.LeavingNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property LeavingNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.LeavingNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.LeavingNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="leavingNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl von Computeknoten, die den Cluster verlassen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingNodeCount">
      <MemberSignature Language="C#" Value="public int PreparingNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PreparingNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.PreparingNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PreparingNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PreparingNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.PreparingNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preparingNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Anzahl von Computeknoten, die vorbereitet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningNodeCount">
      <MemberSignature Language="C#" Value="public int RunningNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RunningNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.RunningNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RunningNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RunningNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.RunningNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runningNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Serverknoten die Aufträge ausgeführt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnusableNodeCount">
      <MemberSignature Language="C#" Value="public int UnusableNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 UnusableNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.UnusableNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property UnusableNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.UnusableNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.UnusableNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unusableNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Serverknoten die unbrauchbar sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeStateCounts.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
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