<Type Name="StartedEvent" FullName="System.Fabric.Chaos.DataStructures.StartedEvent">
  <TypeSignature Language="C#" Value="public sealed class StartedEvent : System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit StartedEvent extends System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.StartedEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StartedEvent&#xA;Inherits ChaosEvent" />
  <TypeSignature Language="F#" Value="type StartedEvent = class&#xA;    inherit ChaosEvent" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Chaos.DataStructures.ChaosEvent</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="8da33-101">Stellt das Ereignis, das erstellt wird, wenn Chaos zum ersten Mal oder nach einer Stop gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="8da33-101">Represents the event that is created when Chaos is started for the first time or following a stop.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartedEvent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StartedEvent.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartedEvent (DateTime timeStamp, System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime timeStamp, class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StartedEvent.#ctor(System.DateTime,System.Fabric.Chaos.DataStructures.ChaosParameters)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.StartedEvent : DateTime * System.Fabric.Chaos.DataStructures.ChaosParameters -&gt; System.Fabric.Chaos.DataStructures.StartedEvent" Usage="new System.Fabric.Chaos.DataStructures.StartedEvent (timeStamp, chaosParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeStamp" Type="System.DateTime" />
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
      </Parameters>
      <Docs>
        <param name="timeStamp"></param>
        <param name="chaosParameters"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChaosParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Chaos.DataStructures.ChaosParameters ChaosParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Chaos.DataStructures.ChaosParameters ChaosParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.StartedEvent.ChaosParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ChaosParameters As ChaosParameters" />
      <MemberSignature Language="F#" Value="member this.ChaosParameters : System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="System.Fabric.Chaos.DataStructures.StartedEvent.ChaosParameters" />
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
        <ReturnType>System.Fabric.Chaos.DataStructures.ChaosParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8da33-102">Ruft das Objekt, das die Parameter zu kapseln, mit denen Chaos gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="8da33-102">Gets the object that encapsulate the parameters with which Chaos was started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StartedEvent.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="startedEvent.Read br" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="br" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="br"><span data-ttu-id="8da33-103">Ein BinaryReader-Objekt</span><span class="sxs-lookup"><span data-stu-id="8da33-103">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="8da33-104">Liest den Status dieses Objekts aus Bytearray.</span><span class="sxs-lookup"><span data-stu-id="8da33-104">Reads the state of this object from byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StartedEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="startedEvent.ToString " />
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
            <span data-ttu-id="8da33-105">Ruft eine Zeichenfolgendarstellung des Ereignisses gestartet.</span><span class="sxs-lookup"><span data-stu-id="8da33-105">Gets a string representation of the started event.</span></span>
            </summary>
        <returns><span data-ttu-id="8da33-106">Eine Zeichenfolgendarstellung des Ereignisses gestartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8da33-106">A string representation of the started event.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StartedEvent.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="startedEvent.Write bw" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bw" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="bw"><span data-ttu-id="8da33-107">Ein BinaryWriter-Objekt.</span><span class="sxs-lookup"><span data-stu-id="8da33-107">A BinaryWriter object.</span></span></param>
        <summary>
            <span data-ttu-id="8da33-108">Schreibt den Status dieses Objekts in ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="8da33-108">Writes the state of this object into a byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>