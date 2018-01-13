<Type Name="StatePersistenceAttribute" FullName="Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute">
  <TypeSignature Language="C#" Value="public sealed class StatePersistenceAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatePersistenceAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatePersistenceAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type StatePersistenceAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Class, Inherited=false)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Gibt an, ob die actorzustands flüchtig sein sollten (im Arbeitsspeicher nur) beibehalten oder überhaupt nicht gespeichert.
            Der Speichertyp, der mit diesem Attribut angegebene muss dem Typ von zustandsanbieter im Dienst Akteur verwendet entsprechen.
            </summary>
    <remarks>
            Das StatePersistence-Attribut nicht von abgeleiteten Klasse geerbt wird, muss jeder Akteur seine StatePersistence bereit auf, wenn ein Akteurtyp ein Attribut StatePersistence nicht actorzustands ist nicht replizierten oder geschrieben.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatePersistenceAttribute (Microsoft.ServiceFabric.Actors.Runtime.StatePersistence statePersistence);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence statePersistence) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute.#ctor(Microsoft.ServiceFabric.Actors.Runtime.StatePersistence)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute : Microsoft.ServiceFabric.Actors.Runtime.StatePersistence -&gt; Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute" Usage="new Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute statePersistence" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="statePersistence" Type="Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" />
      </Parameters>
      <Docs>
        <param name="statePersistence">Gibt an, wie actorzustands für einen Akteur-Dienst gespeichert werden.</param>
        <summary>
            Erstellt eine Instanz von <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute" />.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatePersistence">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute.StatePersistence" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatePersistence As StatePersistence" />
      <MemberSignature Language="F#" Value="member this.StatePersistence : Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" Usage="Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute.StatePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StatePersistence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Get oder Mengen Typ der Enumeration darstellt Status Speicher für den Akteur.
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" />Typ von Zustandsspeicher soll der Akteur darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>