<Type Name="ExecutingFaultsEvent" FullName="System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent">
  <TypeSignature Language="C#" Value="public class ExecutingFaultsEvent : System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ExecutingFaultsEvent extends System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent" />
  <TypeSignature Language="VB.NET" Value="Public Class ExecutingFaultsEvent&#xA;Inherits ChaosEvent" />
  <TypeSignature Language="F#" Value="type ExecutingFaultsEvent = class&#xA;    inherit ChaosEvent" />
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
      <para><span data-ttu-id="17837-101">Stellt das Ereignis, das den Fehler kapselt, die vom Chaos ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="17837-101">Represents the event that encapsulates the faults that are being executed by Chaos.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExecutingFaultsEvent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent.#ctor" />
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
      <MemberSignature Language="C#" Value="public ExecutingFaultsEvent (DateTime timeStampUtc, System.Collections.Generic.List&lt;string&gt; faults);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime timeStampUtc, class System.Collections.Generic.List`1&lt;string&gt; faults) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent.#ctor(System.DateTime,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (timeStampUtc As DateTime, faults As List(Of String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent : DateTime * System.Collections.Generic.List&lt;string&gt; -&gt; System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent" Usage="new System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent (timeStampUtc, faults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeStampUtc" Type="System.DateTime" />
        <Parameter Name="faults" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="timeStampUtc"></param>
        <param name="faults"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Faults">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;string&gt; Faults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;string&gt; Faults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent.Faults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Faults As List(Of String)" />
      <MemberSignature Language="F#" Value="member this.Faults : System.Collections.Generic.List&lt;string&gt;" Usage="System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent.Faults" />
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
        <ReturnType>System.Collections.Generic.List&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17837-102">Ruft die Liste von Fehlern, die Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17837-102">Gets the list of faults that Chaos is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="executingFaultsEvent.Read br" />
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
        <param name="br"><span data-ttu-id="17837-103">Ein BinaryReader-Objekt</span><span class="sxs-lookup"><span data-stu-id="17837-103">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="17837-104">Liest den Status dieses Objekts aus Bytearray.</span><span class="sxs-lookup"><span data-stu-id="17837-104">Reads the state of this object from byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.EndOfStreamException"><span data-ttu-id="17837-105">Das Ende des Streams erreicht ist.</span><span class="sxs-lookup"><span data-stu-id="17837-105">The end of the stream is reached.</span></span> </exception>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="17837-106">Ein E/A-Fehler tritt auf.</span><span class="sxs-lookup"><span data-stu-id="17837-106">An I/O error occurs.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="executingFaultsEvent.ToString " />
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
            <span data-ttu-id="17837-107">Ruft eine Zeichenfolgendarstellung des ausgeführten Ereignisses Fehler ab.</span><span class="sxs-lookup"><span data-stu-id="17837-107">Gets a string representation of the executing faults event.</span></span>
            </summary>
        <returns><span data-ttu-id="17837-108">Eine Zeichenfolgendarstellung des ausgeführten Ereignisses Fehlern.</span><span class="sxs-lookup"><span data-stu-id="17837-108">A string representation of the executing faults event.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ExecutingFaultsEvent.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="executingFaultsEvent.Write bw" />
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
        <param name="bw"><span data-ttu-id="17837-109">Ein BinaryWriter-Objekt.</span><span class="sxs-lookup"><span data-stu-id="17837-109">A BinaryWriter object.</span></span></param>
        <summary>
            <span data-ttu-id="17837-110">Schreibt den Status dieses Objekts in ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="17837-110">Writes the state of this object into a byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="17837-111">Ein E/A-Fehler tritt auf.</span><span class="sxs-lookup"><span data-stu-id="17837-111">An I/O error occurs.</span></span> </exception>
      </Docs>
    </Member>
  </Members>
</Type>