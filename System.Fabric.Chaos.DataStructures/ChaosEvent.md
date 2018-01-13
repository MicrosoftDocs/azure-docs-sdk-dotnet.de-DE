<Type Name="ChaosEvent" FullName="System.Fabric.Chaos.DataStructures.ChaosEvent">
  <TypeSignature Language="C#" Value="public abstract class ChaosEvent : System.Fabric.ByteSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract serializable beforefieldinit ChaosEvent extends System.Fabric.ByteSerializable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ChaosEvent&#xA;Inherits ByteSerializable" />
  <TypeSignature Language="F#" Value="type ChaosEvent = class&#xA;    inherit ByteSerializable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ByteSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="beef3-101">Dies ist die Basisklasse für alle anderen Typen von Ereignissen, die Chaos generiert.</span><span class="sxs-lookup"><span data-stu-id="beef3-101">This is the base class for all the different types of events that Chaos generates</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosEvent.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="System.Fabric.Chaos.DataStructures.ChaosEvent.Kind" />
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
          <para><span data-ttu-id="beef3-102">Beschreibt den Typ des ChaosEvent.</span><span class="sxs-lookup"><span data-stu-id="beef3-102">Describes the type of ChaosEvent.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="beef3-103">Gibt <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" /> den Typ des abgeleiteten ChaosEvent</span><span class="sxs-lookup"><span data-stu-id="beef3-103">Returns <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" /> The type of derived ChaosEvent</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public abstract void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="chaosEvent.Read br" />
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
        <param name="br"><span data-ttu-id="beef3-104">Ein BinaryReader-Objekt</span><span class="sxs-lookup"><span data-stu-id="beef3-104">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="beef3-105">Diese Methode übergeben wird auf die abgeleitete klassifizierten für die Implementierung</span><span class="sxs-lookup"><span data-stu-id="beef3-105">This method is passed onto the derived classed for implementation</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadInheritedMembers">
      <MemberSignature Language="C#" Value="protected void ReadInheritedMembers (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ReadInheritedMembers(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.ReadInheritedMembers(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ReadInheritedMembers (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="member this.ReadInheritedMembers : System.IO.BinaryReader -&gt; unit" Usage="chaosEvent.ReadInheritedMembers br" />
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
        <param name="br"><span data-ttu-id="beef3-106">Ein BinaryReader-Objekt</span><span class="sxs-lookup"><span data-stu-id="beef3-106">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="beef3-107">Diese Methode wird von der abgeleiteten Klasse die geerbten Member aus Bytes zurück konvertieren aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="beef3-107">This method is called from the derived class to convert back the inherited members from bytes</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStampUtc">
      <MemberSignature Language="C#" Value="public DateTime TimeStampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime TimeStampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosEvent.TimeStampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeStampUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.TimeStampUtc : DateTime" Usage="System.Fabric.Chaos.DataStructures.ChaosEvent.TimeStampUtc" />
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
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="beef3-108">"DateTime", wenn das Ereignis aufgetreten ist</span><span class="sxs-lookup"><span data-stu-id="beef3-108">DateTime of when the event occurred</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToBytes">
      <MemberSignature Language="C#" Value="public override byte[] ToBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance unsigned int8[] ToBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.ToBytes" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToBytes () As Byte()" />
      <MemberSignature Language="F#" Value="override this.ToBytes : unit -&gt; byte[]" Usage="chaosEvent.ToBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="beef3-109">Um das Ereignisobjekt Chaos in ein Bytearray zu konvertieren, ist diese Außerkraftsetzung durch den Ereignistyp schreiben startet und ruft dann die Write-Methode der abgeleiteten Klasse</span><span class="sxs-lookup"><span data-stu-id="beef3-109">In order to convert the Chaos event object into a byte array this override starts off by writing the event type and then calls the Write method of the derived class</span></span>
            </summary>
        <returns><span data-ttu-id="beef3-110">Ein Bytearray</span><span class="sxs-lookup"><span data-stu-id="beef3-110">A byte array</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="chaosEvent.ToString " />
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
            <span data-ttu-id="beef3-111">Gibt eine Zeichenfolgendarstellung der-Klasse</span><span class="sxs-lookup"><span data-stu-id="beef3-111">Returns a string representation of the class</span></span>
            </summary>
        <returns><span data-ttu-id="beef3-112">Ein String-Objekt</span><span class="sxs-lookup"><span data-stu-id="beef3-112">A string object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public abstract void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="chaosEvent.Write bw" />
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
        <param name="bw"><span data-ttu-id="beef3-113">Ein BinaryWriter-Objekt</span><span class="sxs-lookup"><span data-stu-id="beef3-113">A BinaryWriter object</span></span></param>
        <summary>
            <span data-ttu-id="beef3-114">Diese Methode wird auf die abgeleiteten Klassen für die Implementierung übergeben.</span><span class="sxs-lookup"><span data-stu-id="beef3-114">This method is passed onto the derived classes for implementation</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteInheritedMembers">
      <MemberSignature Language="C#" Value="protected void WriteInheritedMembers (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void WriteInheritedMembers(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.WriteInheritedMembers(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub WriteInheritedMembers (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="member this.WriteInheritedMembers : System.IO.BinaryWriter -&gt; unit" Usage="chaosEvent.WriteInheritedMembers bw" />
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
        <param name="bw"><span data-ttu-id="beef3-115">Ein BinaryWriter-Objekt</span><span class="sxs-lookup"><span data-stu-id="beef3-115">A BinaryWriter object</span></span></param>
        <summary>
            <span data-ttu-id="beef3-116">Diese Methode wird von der abgeleiteten Klasse die geerbten Member in Bytes konvertiert aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="beef3-116">This method is called from the derived class to convert the inherited members into bytes</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>