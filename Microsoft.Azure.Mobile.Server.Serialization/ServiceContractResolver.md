<Type Name="ServiceContractResolver" FullName="Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver">
  <TypeSignature Language="C#" Value="public class ServiceContractResolver : System.Net.Http.Formatting.JsonContractResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceContractResolver extends System.Net.Http.Formatting.JsonContractResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceContractResolver&#xA;Inherits JsonContractResolver" />
  <TypeSignature Language="F#" Value="type ServiceContractResolver = class&#xA;    inherit JsonContractResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Net.Http.Formatting.JsonContractResolver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die Standardeinstellung <see cref="T:Newtonsoft.Json.Serialization.IContractResolver" /> verwendeten <see cref="T:System.Net.Http.Formatting.JsonMediaTypeFormatter" /> jedoch durch das Hinzufügen von Unterstützung gemischter Schreibweise Serialisierung. Er verwendet des Formatierungsprogramms <see cref="T:System.Net.Http.Formatting.IRequiredMemberSelector" /> auf die erforderlichen Elemente auszuwählen und erkennt die <see cref="T:System.SerializableAttribute" /> geben Anmerkung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceContractResolver (System.Net.Http.Formatting.MediaTypeFormatter formatter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.Formatting.MediaTypeFormatter formatter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver.#ctor(System.Net.Http.Formatting.MediaTypeFormatter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (formatter As MediaTypeFormatter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver : System.Net.Http.Formatting.MediaTypeFormatter -&gt; Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" Usage="new Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver formatter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="formatter" Type="System.Net.Http.Formatting.MediaTypeFormatter" />
      </Parameters>
      <Docs>
        <param name="formatter">Die <see cref="T:System.Net.Http.Formatting.MediaTypeFormatter" /> zum Auflösen von Erforderlicher Member verwendet.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" /> mit einer bestimmten <paramref name="formatter" /> zum Auflösen von erforderliche Member.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvePropertyName">
      <MemberSignature Language="C#" Value="protected override string ResolvePropertyName (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string ResolvePropertyName(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver.ResolvePropertyName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ResolvePropertyName (propertyName As String) As String" />
      <MemberSignature Language="F#" Value="override this.ResolvePropertyName : string -&gt; string" Usage="serviceContractResolver.ResolvePropertyName propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
  </Members>
</Type>