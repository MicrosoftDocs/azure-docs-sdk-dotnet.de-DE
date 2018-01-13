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
            Dies ist die Basisklasse für alle anderen Typen von Ereignissen, die Chaos generiert.
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
          <para>Beschreibt den Typ des ChaosEvent.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" /> den Typ des abgeleiteten ChaosEvent</para>
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
        <param name="br">Ein BinaryReader-Objekt</param>
        <summary>
            Diese Methode übergeben wird auf die abgeleitete klassifizierten für die Implementierung
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
        <param name="br">Ein BinaryReader-Objekt</param>
        <summary>
            Diese Methode wird von der abgeleiteten Klasse die geerbten Member aus Bytes zurück konvertieren aufgerufen.
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
            "DateTime", wenn das Ereignis aufgetreten ist
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
            Um das Ereignisobjekt Chaos in ein Bytearray zu konvertieren, ist diese Außerkraftsetzung durch den Ereignistyp schreiben startet und ruft dann die Write-Methode der abgeleiteten Klasse
            </summary>
        <returns>Ein Bytearray</returns>
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
            Gibt eine Zeichenfolgendarstellung der-Klasse
            </summary>
        <returns>Ein String-Objekt</returns>
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
        <param name="bw">Ein BinaryWriter-Objekt</param>
        <summary>
            Diese Methode wird auf die abgeleiteten Klassen für die Implementierung übergeben.
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
        <param name="bw">Ein BinaryWriter-Objekt</param>
        <summary>
            Diese Methode wird von der abgeleiteten Klasse die geerbten Member in Bytes konvertiert aufgerufen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>