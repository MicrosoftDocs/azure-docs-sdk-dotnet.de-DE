<Type Name="SafetyCheck" FullName="System.Fabric.SafetyCheck">
  <TypeSignature Language="C#" Value="public abstract class SafetyCheck" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SafetyCheck extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SafetyCheck" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SafetyCheck" />
  <TypeSignature Language="F#" Value="type SafetyCheck = class" />
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
      <para>
            Stellt eine sicherheitsprüfung, die derzeit für einen Knoten ausgeführt wird.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal SafetyCheck (System.Fabric.SafetyCheckKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.SafetyCheckKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SafetyCheck.#ctor(System.Fabric.SafetyCheckKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New (kind As SafetyCheckKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.SafetyCheck : System.Fabric.SafetyCheckKind -&gt; System.Fabric.SafetyCheck" Usage="new System.Fabric.SafetyCheck kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.SafetyCheckKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para>Die Art der Sicherheit.</para>
        </param>
        <summary>
          <para>
            Instanziiert eine <see cref="T:System.Fabric.SafetyCheck" /> Objekt des angegebenen Typs. Kann nur von abgeleiteten Klassen aufgerufen werden.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.SafetyCheckKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.SafetyCheckKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SafetyCheck.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As SafetyCheckKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.SafetyCheckKind" Usage="System.Fabric.SafetyCheck.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft den Typ der sicherheitsüberprüfung, die ausgeführt wird.
            </para>
        </summary>
        <value>
          <para>Der Typ der sicherheitsüberprüfung, die ausgeführt wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>