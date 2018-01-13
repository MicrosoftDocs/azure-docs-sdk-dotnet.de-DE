<Type Name="ConnectionResetSharedKeyInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner">
  <TypeSignature Language="C#" Value="public class ConnectionResetSharedKeyInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionResetSharedKeyInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionResetSharedKeyInner" />
  <TypeSignature Language="F#" Value="type ConnectionResetSharedKeyInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionResetSharedKeyInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ConnectionResetSharedKeyInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionResetSharedKeyInner (int keyLength);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 keyLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyLength As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner : int -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner keyLength" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyLength" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="keyLength">Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssellänge zurücksetzen, muss zwischen 1 und 128.</param>
        <summary>
            Initialisiert eine neue Instanz der ConnectionResetSharedKeyInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyLength">
      <MemberSignature Language="C#" Value="public int KeyLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 KeyLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.KeyLength" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyLength As Integer" />
      <MemberSignature Language="F#" Value="member this.KeyLength : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.KeyLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Schlüssellänge virtuelles Netzwerk Verbindung gemeinsam zurücksetzen, muss zwischen 1 und 128.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="connectionResetSharedKeyInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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