<Type Name="StoppedEvent" FullName="System.Fabric.Chaos.DataStructures.StoppedEvent">
  <TypeSignature Language="C#" Value="public sealed class StoppedEvent : System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit StoppedEvent extends System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.StoppedEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StoppedEvent&#xA;Inherits ChaosEvent" />
  <TypeSignature Language="F#" Value="type StoppedEvent = class&#xA;    inherit ChaosEvent" />
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
      <para><span data-ttu-id="363a3-101">Stellt das Chaos-Ereignis, das erstellt wird, wenn Chaos aus irgendeinem Grund beendet wird.</span><span class="sxs-lookup"><span data-stu-id="363a3-101">Represents the Chaos event that is created when Chaos is stopped for some reason.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StoppedEvent.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="stoppedEvent.Read br" />
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
        <param name="br"><span data-ttu-id="363a3-102">Ein BinaryReader-Objekt</span><span class="sxs-lookup"><span data-stu-id="363a3-102">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="363a3-103">Liest den Status dieses Objekts aus Bytearray.</span><span class="sxs-lookup"><span data-stu-id="363a3-103">Reads the state of this object from byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.EndOfStreamException"><span data-ttu-id="363a3-104">Das Ende des Streams erreicht ist.</span><span class="sxs-lookup"><span data-stu-id="363a3-104">The end of the stream is reached.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.StoppedEvent.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="System.Fabric.Chaos.DataStructures.StoppedEvent.Reason" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363a3-105">Ruft den Grund für das Anhalten ab.</span><span class="sxs-lookup"><span data-stu-id="363a3-105">Gets the reason for stopping.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StoppedEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="stoppedEvent.ToString " />
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
            <span data-ttu-id="363a3-106">Ruft eine Zeichenfolgendarstellung des beendeten Ereignisses ab.</span><span class="sxs-lookup"><span data-stu-id="363a3-106">Gets a string representation of the stopped event.</span></span>
            </summary>
        <returns><span data-ttu-id="363a3-107">Eine Zeichenfolgendarstellung des Ereignisses beendet.</span><span class="sxs-lookup"><span data-stu-id="363a3-107">A string representation of the stopped event.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StoppedEvent.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="stoppedEvent.Write bw" />
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
        <param name="bw"><span data-ttu-id="363a3-108">Ein BinaryWriter-Objekt.</span><span class="sxs-lookup"><span data-stu-id="363a3-108">A BinaryWriter object.</span></span></param>
        <summary>
            <span data-ttu-id="363a3-109">Schreibt den Status dieses Objekts in ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="363a3-109">Writes the state of this object into a byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="363a3-110">Ein E/A-Fehler tritt auf.</span><span class="sxs-lookup"><span data-stu-id="363a3-110">An I/O error occurs.</span></span> </exception>
      </Docs>
    </Member>
  </Members>
</Type>