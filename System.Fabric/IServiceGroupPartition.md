<Type Name="IServiceGroupPartition" FullName="System.Fabric.IServiceGroupPartition">
  <TypeSignature Language="C#" Value="public interface IServiceGroupPartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceGroupPartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IServiceGroupPartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceGroupPartition" />
  <TypeSignature Language="F#" Value="type IServiceGroupPartition = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>Können Gruppenmitglieder innerhalb einer Dienstgruppe Dienst bereitgestellten umwandeln <see cref="T:System.Fabric.IStatefulServicePartition" /> oder <see cref="T:System.Fabric.IStatelessServicePartition" /> auf eine <see cref="T:System.Fabric.IServiceGroupPartition" /> auf die Methoden zugreifen, die für Elemente in Dienstgruppen spezifisch sind.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ResolveMember&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T ResolveMember&lt;T&gt; (Uri name) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!T ResolveMember&lt;class T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServiceGroupPartition.ResolveMember``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveMember(Of T As Class) (name As Uri) As T" />
      <MemberSignature Language="F#" Value="abstract member ResolveMember : Uri -&gt; 'T (requires 'T : null)" Usage="iServiceGroupPartition.ResolveMember name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
          <para>Der Typ des Diensts Members, der aufgelöst werden sollen.</para>
        </typeparam>
        <param name="name">
          <para>Die <c>Fabric: /</c> Name des Members, um Sie zu beheben.</para>
        </param>
        <summary>
          <para>Ermöglicht es das Mitglied Direktzugriff mit den anderen Mitgliedern der Gruppe "Service" abgerufen.</para>
        </summary>
        <returns>
          <para>Gibt das Element, das anhand des Namens, als ein Objekt des angegebenen Typs angegeben ist zurück.</para>
        </returns>
        <remarks>
          <para>Die <see cref="M:System.Fabric.IServiceGroupPartition.ResolveMember``1(System.Uri)" /> Methode ermöglicht ein Gruppenmitglied Dienst um einen direkten Verweis auf den anderen Elementen in der Gruppe zu erhalten. Die direkte Objekt Kommunikation mit den anderen Elementen erfordert keine Kommunikation außerhalb der Computer oder virtuelle Maschine, entweder für die Kommunikation mit dem Dienst benennen, beheben Sie das Element oder über einige externe Transport zum Senden der tatsächlichen Befehle, um das Element.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>