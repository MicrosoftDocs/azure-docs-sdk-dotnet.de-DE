<Type Name="TestCommandProgress" FullName="System.Fabric.TestCommandProgress">
  <TypeSignature Language="C#" Value="public abstract class TestCommandProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TestCommandProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TestCommandProgress" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TestCommandProgress" />
  <TypeSignature Language="F#" Value="type TestCommandProgress = class" />
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
            Die Basisklasse für die Objekte ausgeführt.
            </summary>
    <remarks>
            Diese Klasse gibt die TestCommandProgressState zurück.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal TestCommandProgress ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TestCommandProgress.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public System.Fabric.TestCommandProgressState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.TestCommandProgressState State" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TestCommandProgress.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As TestCommandProgressState" />
      <MemberSignature Language="F#" Value="member this.State : System.Fabric.TestCommandProgressState" Usage="System.Fabric.TestCommandProgress.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zustand, bei dem die Aktion jetzt lautet, ab: ausgeführt "," abgeschlossen "," Faulted "oder" ungültig
            </summary>
        <value>Der Zustand des testbefehls.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TestCommandProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="testCommandProgress.ToString " />
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
            Gibt die Zeichenfolgendarstellung des Zustands zurück
            </summary>
        <returns>Darstellung des Status</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>