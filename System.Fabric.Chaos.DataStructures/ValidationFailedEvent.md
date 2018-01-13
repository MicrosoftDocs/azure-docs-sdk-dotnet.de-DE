<Type Name="ValidationFailedEvent" FullName="System.Fabric.Chaos.DataStructures.ValidationFailedEvent">
  <TypeSignature Language="C#" Value="public sealed class ValidationFailedEvent : System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ValidationFailedEvent extends System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ValidationFailedEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ValidationFailedEvent&#xA;Inherits ChaosEvent" />
  <TypeSignature Language="F#" Value="type ValidationFailedEvent = class&#xA;    inherit ChaosEvent" />
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
      <para>Stellt das Chaos-Ereignis, das erstellt wird, wenn die Überprüfung schlägt fehl, und kapselt Informationen, warum die Validierung fehlgeschlagen ist.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ValidationFailedEvent.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="validationFailedEvent.Read br" />
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
            Liest den Status dieses Objekts aus Bytearray.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.EndOfStreamException">Das Ende des Streams erreicht ist. </exception>
        <exception cref="T:System.IO.IOException">Ein E/A-Fehler tritt auf. </exception>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ValidationFailedEvent.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="System.Fabric.Chaos.DataStructures.ValidationFailedEvent.Reason" />
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
            Ruft die Zeichenfolgendarstellung der Grund für den Validierungsfehler ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ValidationFailedEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="validationFailedEvent.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der fehlerhaften Validierungsereignisses ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der Überprüfung Fehler Ereignis.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ValidationFailedEvent.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="validationFailedEvent.Write bw" />
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
        <param name="bw">Ein BinaryWriter-Objekt.</param>
        <summary>
            Schreibt den Status dieses Objekts in ein Bytearray.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.IOException">Ein E/A-Fehler tritt auf. </exception>
      </Docs>
    </Member>
  </Members>
</Type>